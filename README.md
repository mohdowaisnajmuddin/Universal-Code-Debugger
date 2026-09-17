🐛 Universal Code Debugger — AI-Powered Debugging Assistant

🔗 Live demo: https://universalcodedebugger.vercel.app/

An AI-powered debugging tool that analyzes pasted code across multiple languages, identifies errors with line-level precision, and explains the fix in plain language.

✨ What it actually does

🌐 Multi-language support. Python, JavaScript, TypeScript, C, C++, Java, Go, Rust, and PHP, selectable from a language dropdown.

📝 In-browser code editor with syntax highlighting and line numbers.

🔍 One-click debugging. Clicking "Debug" analyzes the pasted code and returns: the actual output (or the error), a count of errors found, the specific line and error type (e.g. "L2 · syntax · Invalid syntax 'efeg' at end of line"), and a plain-language debug explanation of what's wrong and how to fix it.

✅ Apply Fix, Copy, and Download actions on the result, so the corrected code can be used immediately.

🔄 Reset to clear the editor and start over.

🛠️ Tech stack

[Fill in — frontend framework, which LLM/API powers the debugging analysis, hosting]

⚙️ Running locally

git clone 

https://github.com/yourself/universal-code-debugger.git

cd universalcodedebugger

npm install

npm run dev

📝 Notes
If this tool calls an LLM API to generate the debug explanation, document which model/API and any rate limits or cost considerations here — that's a legitimate detail worth being specific about rather than vague on.

📸 Screenshots

<img width="1919" height="886" alt="Screenshot 2026-09-14 184938" src="https://github.com/user-attachments/assets/aa23ed2b-10a0-4306-b21c-5197d465afc6" />



📄 License

MIT License

Copyright (c) 2026 Mohammed Owais Najmuddin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
