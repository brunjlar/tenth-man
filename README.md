# **Tenth Man: Iterative AI Refinement**

This repository contains a single-page web application that uses an iterative AI process to generate, critique, and refine text-based responses based on the 'Tenth Man' principle.

The application allows a user to input a prompt, which is sent to an initial AI assistant. A second AI, acting as a "Tenth Man," is then tasked with challenging the initial response. This cycle of response, critique, and synthesis can be repeated on-demand to produce a more robust and well-considered final answer.

## **How it Works: The Tenth Man Principle**

This application is built on the 'Tenth Man' principle, a rule that originated with the Israeli intelligence community (Mossad) following the strategic surprise of the 1973 Yom Kippur War. To prevent future failures of imagination and avoid the trap of groupthink, a new protocol was established: if a group of ten analysts comes to a unanimous conclusion, a tenth person is designated to challenge that consensus, no matter how unlikely their dissenting argument may seem.

This forces the group to re-examine their assumptions from the ground up and strengthens the final conclusion. The concept has been popularized in media, notably in the movie *World War Z*.

In this app, one AI instance generates a response, and a second 'Tenth Man' AI is specifically prompted to find flaws and offer a contrarian critique. This cycle can be repeated multiple times, with each iteration synthesizing the previous response and critique into a more robust and well-considered final answer.

## **Features**

* **On-Demand Refinement:** Instead of choosing the number of iterations in advance, you can refine the AI's response step-by-step, deciding after each cycle whether to continue.  
* **Side-by-Side View:** Clearly see the generated response next to its corresponding critique for easy comparison.  
* **Full Navigation Control:** A floating navigation hub appears once results are generated, allowing you to jump to the previous, next, or **very last** result, as well as instantly return to the top.  
* **Share Everything:** A dedicated button in the navigation hub compiles the entire session—prompt, responses, and critiques—into a single, cleanly formatted text block for easy sharing or saving.  
* **Shareable Content:** Easily copy or share the initial prompt, any individual response, or any critique.  
* **System Prompting:** Uses dedicated system instructions to guide the persona of the "Expert Assistant," the "Tenth Man," and the "Synthesizer" for better results.  
* **Secure API Key Storage:** Your API key is saved locally in your browser's storage and is never transmitted anywhere except directly to the Google AI API.

## **How to Use**

1. **Download the Code:** Clone this repository or download the index.html file.  
2. **Open in Browser:** Open the index.html file in any modern web browser.  
3. **Enter API Key:** Provide your Google AI API key. The application uses the gemini-2.5-pro model.  
4. **Write a Prompt:** Enter the prompt you want the AI to respond to.  
5. **Start Refinement:** Click the "Start Refinement" button. The app will generate the initial response and its first critique.  
6. **Refine Further:** If you are not satisfied with the result, click the "Refine Further" button to run another cycle of synthesis and critique. Repeat as many times as you see fit.

## **License**

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).