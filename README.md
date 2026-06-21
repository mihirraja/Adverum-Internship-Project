# Adverum Internship Project

This repository contains a redacted version of my internship presentation and a summary of the end-to-end work I completed during the project.

## Internship presentation

- [Internship presentation slides](docs/internship-presentation-redacted.pdf)

## Project focus

My internship work centered on building and improving document review workflows. The goal was to make it easier to move from raw documents to useful review outputs by extracting relevant information, presenting it clearly, and making the results easier to verify.

## End-to-end process

The project followed an end-to-end workflow:

1. Ingest documents or source files into the application.
2. Extract text and structured information from the uploaded content.
3. Clean and normalize the extracted data so it could be reviewed consistently.
4. Identify important sections, patterns, or fields for downstream review.
5. Present the results in a document review interface.
6. Validate the output against the original document.
7. Iterate on the pipeline to improve accuracy, speed, and usability.

This process helped connect the technical backend work with the user-facing review experience. Each step affected the next one, so improvements to parsing, formatting, or performance directly improved the quality of the final review workflow.

## Document review app

The document review app was designed to help users inspect documents more efficiently. Instead of manually searching through every page, the app supported a more guided review process by extracting meaningful text and organizing the results in a clearer interface.

Core areas of work included:

- Building the flow from document input to review-ready output.
- Improving text extraction and handling inconsistently formatted documents.
- Making outputs easier to compare against the original source document.
- Designing the review process so users could understand where results came from.
- Iterating on the interface and pipeline based on accuracy, reliability, and usability.

## Optimizations

Optimization was an important part of the project. The work was not only about making the app faster, but also about reducing repeated processing, improving reliability, and making the review experience feel smoother.

Examples of optimization work included:

- Streamlining document processing steps.
- Reducing unnecessary recomputation during review.
- Improving how extracted text was organized before display.
- Making edge cases easier to handle when documents had inconsistent structure.
- Keeping outputs concise so reviewers could focus on the most important information.

## What I learned

This internship helped me better understand how to build a complete application workflow, not just isolated features. I learned how document ingestion, extraction, processing, interface design, and validation all connect in an end-to-end product.

I also learned that verification is central to document review tools. A result is only useful if a user can trace it back to the source and decide whether it is accurate. That shaped how I thought about transparency, output formatting, and user trust.

Finally, I learned that optimization includes both technical and product improvements. Faster processing matters, but so do clearer results, fewer manual steps, better error handling, and a smoother review experience.
