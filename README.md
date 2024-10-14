# Large Document Summarization with LangChain and LlamaParse

## Overview

This Jupyter notebook demonstrates advanced techniques for summarizing large documents, specifically focusing on financial reports. It compares two different methods of PDF parsing and utilizes LangChain's Refine summarization technique to generate comprehensive summaries.

## Key Features

1. **Dual PDF Parsing Methods:**
   - Basic extraction using PyPDFLoader
   - Advanced extraction using LlamaParse

2. **LangChain Refine Summarization:**
   - Implements the Refine chain for processing large documents
   - Custom prompt design for initial summarization and refinement

3. **Multiple Document Analysis:**
   - Processes Home Depot's annual report, proxy statement, and quarterly report

4. **Comparative Analysis:**
   - Evaluates the quality and depth of summaries produced by each method

## Requirements

- Python 3.7+
- Libraries: langchain, llama_parse, pandas, nest_asyncio, dotenv
- Azure OpenAI API access

## Setup

1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Set up your `.env` file with Azure OpenAI API and Llama Cloud API credentials

## Usage

1. Open the Jupyter notebook `Large_Doc_Summarization.ipynb`
2. Run the cells sequentially to see the summarization process and results
3. Compare the outputs from PyPDFLoader and LlamaParse methods

## Key Sections

1. Data Preparation
2. Basic Data Extraction (PyPDFLoader)
3. Advanced Data Extraction (LlamaParse)
4. Refine Chain Implementation
5. Summary Generation
6. Final Summarization and Comparison

## Conclusion

The notebook provides insights into the strengths and weaknesses of each summarization approach, helping users choose the most suitable method for their specific needs in financial document analysis.

## License

MIT License

Copyright (c) 2024 Nam

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

## Contributors

Nam Tran
````

This updated README now includes your name as the contributor and incorporates the MIT license. The MIT license is a permissive open-source license that allows others to use, modify, and distribute your code with minimal restrictions, as long as they include the original copyright notice and license text.
