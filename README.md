This was my first time using Postman, and I must say it was a fun challenge! The tool made it easy to send HTTP requests, analyze responses, and troubleshoot errors. I was able to efficiently test the registration process, learn about REST APIs, and understand how web services communicate. The entire process was smooth, and it helped me get familiar with working with APIs in a real-world context.

Solutions
This repository contains the solutions for all three problems. Each solution is housed in its respective file/folder, with a brief description of the approach used to solve the problem.

Problem 1: 
Problem 2: In this problem, we were tasked with decrypting a given encrypted text using a specific key. After decrypting the text, we encountered Unicode representations of emojis in the format U+<hex code>. To convert these to actual emojis, we used a regular expression to identify the Unicode sequences and replaced them with their corresponding emoji characters. This process allowed us to transform the decrypted text into a readable format containing both numbers and emojis. The final output displayed the fully decoded text with the emojis rendered correctly.
Problem 3: In this problem, we were tasked with extracting a hidden IP address from a passage of text where the address was represented using English number words. We converted the number words (e.g., "zero", "one", "point") into their numeric equivalents, with "point" serving as a separator between IP address segments. We used a regular expression to identify the sequences of number words. After conversion, we validated the segments to ensure they formed a valid IP address (i.e., each segment was between 0 and 255). If a valid IP was found, we returned it; otherwise, we returned an empty string.



