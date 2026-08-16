# Report Review Notes

## Application Result

### Finding

The PDF `Images/GIP_D3_TTNT_HK243.pdf` identifies the legal company name **Công ty CP Dịch vụ Dữ liệu CNTT Vi Na**. The user confirmed that this legal entity is GreenNode, so the document content matches the internship enterprise.

The remaining issue is the caption in `KetQuaXetTuyen.tex`, which incorrectly says:

```latex
\caption{Kết quả xét tuyển công ty GIP}
```

### Required fix

Update the caption to identify GreenNode:

```latex
\caption{GreenNode internship acceptance result}
```

The filename `GIP_D3_TTNT_HK243.pdf` is confusing but does not affect LaTeX compilation. If desired, rename it to `GreenNode_application_result.pdf` and update the include path; this is optional.

### Format check

The current `figure` environment and `\includegraphics[width=1\linewidth]{...}` syntax are valid LaTeX. No format fix is needed.
