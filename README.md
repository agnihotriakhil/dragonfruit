Please look at the `report.pdf` for a detailed thought process and summary of the challenge, and `notebook.ipynb` for the code. Thank you

###  Update after feedback

Since the current data storage scheme is too large, we would try out a few different ways to bypass this and decide based on the emperical results if those schemas are plausible:

- Tiling / Chunking : this refers to chunking areas of the image such that the resolution goes down from $(10^5, 10^5)$ to $(10^3, 10^3)$. We will do this by averaging the values of the pixels around the target pixel to capture local information. In this case the worst case space required would be ~125 KB.
- JPEG / PNG formats : these formats let the user enjoy lossy and lossless storage capabilities respectively. Based on the needs of the scientists, we would emply one of these methods, depending on the quality of images required.


**Note.** Please note that this is just a rough estimate solution since there is a delay in feedback and it is an open ended problem. If there were specific requirements for a solution or hard time and computational constraints, the solution would be more structured and accurate. Thank you very much for your time and understanding! 
