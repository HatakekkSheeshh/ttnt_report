# Report Review Notes

## Weekly Tasks Roadmap

The weekly-task section now follows a connected roadmap: agent foundations in Month 1, SRE Agent development beginning in the first weeks of Month 2, sandbox research as a supporting execution-environment capability, and concurrent SRE Agent plus sandbox work during the final two weeks. The roadmap introduction uses first-person narration and explains that the SRE Agent was built from the Month 1 foundations rather than received as a transferred project. The final phase covers harness development, infrastructure research, sandbox continuation, and the Deep Agent proposal.

## Application Result: Caption Clarification

The PDF `Images/GIP_D3_TTNT_HK243.pdf` identifies the legal company name **Công ty CP Dịch vụ Dữ liệu CNTT Vi Na**. The user confirmed that this legal entity is GreenNode, so the PDF content is consistent with the internship enterprise.

### Required fix

The problem is the outdated/incorrect caption, not the PDF content. Update `KetQuaXetTuyen.tex` from:

```latex
\caption{Kết quả xét tuyển công ty GIP}
```

to:

```latex
\caption{GreenNode internship acceptance result}
```

The image filename `GIP_D3_TTNT_HK243.pdf` is also confusing. It may be renamed to a descriptive name such as `GreenNode_application_result.pdf`, but renaming is optional because the LaTeX format itself is valid.

### Format check

The current `figure` environment and `\includegraphics[width=1\linewidth]{...}` syntax are valid LaTeX. No format correction is needed.
