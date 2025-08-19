## Task: Retrieve Photometric Correction Code

You are an expert code retrieval agent. Your job is to scan all files in the current folder (including subfolders) and identify any code or configuration related to the following topics:

- Exposure balancing (曝光均衡)
- White balance (白平衡)
- Vignetting correction, including off-center vignetting (暗角校正，含偏心)
- EMoR response curves (EMoR 响应曲线)

### Instructions:
1. Search through all source code files, configuration files, and scripts in this folder.
2. Collect and return **only the code snippets and function definitions** directly relevant to the above topics.
3. For each match, provide:
   - The file path
   - The function or class name (if applicable)
   - The relevant code snippet (minimum necessary context, do not dump entire files)
   - A short explanation (1–2 sentences) of how it relates to exposure balancing, white balance, vignetting, or EMoR.
4. If no related code is found, explicitly state: "No related code found."
