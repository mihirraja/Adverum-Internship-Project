# Adverum Internship Project

This repository contains a redacted version of my internship presentation and a summary of the end-to-end work I completed during the project.

## Internship presentation

- [Internship presentation slides](docs/internship-presentation-redacted.pdf)

## Project focus

My internship work centered on building an end-to-end data and machine learning workflow. A major part of the project was taking raw data spread across multiple SQL tables and joining it together across multiple days to create a usable dataset for modeling.

I also worked on a document review app that helped make review workflows more efficient by extracting relevant information, presenting it clearly, and making the results easier to verify.

## End-to-end process

The project followed an end-to-end workflow:

1. Understand the available data sources and how the SQL tables related to each other.
2. Join data from multiple tables across multiple days to create one consistent modeling dataset.
3. Clean and normalize the data so each row could be used reliably for machine learning.
4. Engineer features from the joined dataset and prepare the target variable.
5. Train and compare different machine learning models.
6. Evaluate results and interpret which model choices made sense for the size and quality of the dataset.
7. Iterate on the pipeline to improve data quality, model performance, and usability.

This process helped me understand how much of machine learning work happens before model training. The SQL joins, data cleaning, and dataset construction were just as important as the modeling step because the models could only perform well if the training data was reliable.

## Machine learning work

After building a usable dataset, I experimented with several modeling approaches, including logistic regression and random forest models. Logistic regression provided a simpler and more interpretable baseline, while random forest gave me a way to test a more flexible non-linear model.

I also considered the tradeoff between model complexity and dataset size. More heavyweight models might have worked with more data, but the dataset was relatively small, so simpler models were more practical and easier to evaluate responsibly. This helped me focus on choosing models that matched the data instead of defaulting to the most complex option.

## Document review app

The document review app was designed to help users inspect documents more efficiently. Instead of manually searching through every page, the app supported a more guided review process by extracting meaningful text and organizing the results in a clearer interface.

Core areas of work included:

- Building the flow from document input to review-ready output.
- Improving text extraction and handling inconsistently formatted documents.
- Making outputs easier to compare against the original source document.
- Designing the review process so users could understand where results came from.
- Iterating on the interface and pipeline based on accuracy, reliability, and usability.

## Optimizations

Optimization was an important part of both the data pipeline and the document review app. The work was not only about making things faster, but also about reducing repeated processing, improving reliability, and making the outputs easier to trust.

Examples of optimization work included:

- Improving SQL joins and data preparation steps so the final ML dataset was more usable.
- Streamlining document processing steps.
- Reducing unnecessary recomputation during review.
- Improving how extracted text was organized before display.
- Making edge cases easier to handle when documents had inconsistent structure.
- Keeping outputs concise so reviewers could focus on the most important information.

## What I learned

This internship helped me better understand how to build a complete data and application workflow, not just isolated features. I learned how raw SQL data, data cleaning, feature preparation, model training, evaluation, and application design all connect in an end-to-end product.

I also learned that model selection depends heavily on the dataset. Logistic regression and random forest were useful because they fit the scale of the data and gave me interpretable ways to compare performance. With a small dataset, heavier models could have overcomplicated the project without necessarily improving the result.

Finally, I learned that verification is central to both machine learning and document review tools. A result is only useful if a user can understand where it came from and decide whether it is accurate. That shaped how I thought about transparency, output formatting, user trust, and responsible model evaluation.
