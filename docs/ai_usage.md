# AI Use Log

- **Tool/model & version**: ChatGPT GPT-5 (Sep 2025)  
- **What I asked for**: Explain how to use `range()` in a Python for loop  
- **Snippet of prompt(s)**: "Show me how to loop from 1 to 10 in Python"  
- **What I changed before committing**: Adjusted loop to start at 0, added comments, cleaned up formatting  
- **How I verified correctness**: Ran code in Colab, confirmed output printed 0–9 as expected  

---

- **Tool/model & version**: Gemini 1.5  
- **What I asked for**: Help with Rosalind #4 – reading files in Python  
- **Snippet of prompt(s)**: "How to open and read a text file line by line in Python?"  
- **What I changed before committing**: Used `with open("practice.txt","r") as data` instead of Gemini’s suggested path, added `.rstrip()` to clean newlines  
- **How I verified correctness**: Uploaded `practice.txt` to Colab, confirmed file contents printed correctly  

---

- **Tool/model & version**: ChatGPT GPT-5  
- **What I asked for**: How to install and test Biopython in Colab  
- **Snippet of prompt(s)**: "Give me a simple test to check if Biopython is installed"  
- **What I changed before committing**: Added `!pip install biopython` in Colab, then imported only the required function (`from Bio.Seq import Seq`)  
- **How I verified correctness**: Ran `print(Seq("ATGC").complement())` and confirmed output was `TACG`  

---

- **Tool/model & version**: Claude 3 Sonnet  
- **What I asked for**: Debugging Rosalind #3 (loops and conditions)  
- **Snippet of prompt(s)**: "Why does my while loop run forever in Python?"  
- **What I changed before committing**: Added `a += 1` inside the while loop, fixed indentation issues  
- **How I verified correctness**: Ran code in Colab, confirmed it printed exactly 3 iterations and stopped as expected  
