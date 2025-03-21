Softwrap 2.1.2 – Blender 4.4 Fix
This is a patched version of the Softwrap 2.1.2 add-on, originally developed by Jean Da Costa Machado, then modified by /danemadsen to work with 3.1 , further modified by me to work with 4.4

The original version didn’t work out-of-the-box with Blender 4.4, so I modified it until it did. I'm not an expert — just someone who wanted it working — so take this as a "working" patch.

✅ What’s Changed
Updated the add-on to work with Blender 4.4 and Python 3.11.
Recompiled the Cython core module softwrap_core2.pyd using the correct Python version and compiler setup.
Cleaned up the file structure to keep it minimal but developer-friendly.

🛠 Developer Info
If you want to modify or recompile the core, the core/ folder includes:
core2.pyx – the Cython source
setup.py – the build script
You’ll need Python 3.11.x, Cython, and Visual Studio Build Tools to rebuild.

🧠 If Something Breaks
If you run into issues:
Make sure you're using the correct Python version (3.11, not 3.13 or 3.10).
If it's a weird error and you're not sure how to fix it — ask ChatGPT. That’s how I got this working in the first place.

🔗 Original Author
Jean Da Costa Machado
Softwrap Manual

📜 License
This version, like the original, is licensed under GNU GPL v3.0.
You’re free to use, modify, and redistribute — just keep the license with it.
