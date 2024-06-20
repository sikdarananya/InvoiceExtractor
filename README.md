# Invoice Extractor with Gemini Pro Vision

This Python project leverages Gemini Pro Vision's multimodal capabilities to extract key data from invoice documents (PDFs, images). It offers advantages like:

# Versatility: 
Handles diverse invoice layouts with Gemini Pro Vision's understanding of both text and visuals.
# Accuracy: 
Combines Gemini Pro Vision's language processing with potential rule-based parsing for enhanced precision.
# Flexibility: 
Can be customized to target specific invoice fields using clear prompts and potential rule-based refinements.

# Conceptual Workflow:

Upload invoice to Gemini Pro Vision:
Integrate the Gemini Pro Vision API into your Python script.
Send the invoice document (PDF or image) along with a prompt specifying the desired information to extract (e.g., "Extract total amount from this invoice").
Process Gemini Pro Vision response:
The response might include extracted data points or require further parsing.
Refine and consolidate data (optional):
Depending on the complexity of invoices and Gemini Pro Vision's output, you might need to apply rule-based parsing or regular expressions to clean and structure the extracted data.
Save output:
Store the extracted information in a structured format (CSV, JSON) for further use.

Use streamlit to develop the frontend
