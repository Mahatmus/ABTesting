## AB Testing
In this project, I demonstrate a few approaches to testing the differences in results, based on different treatments.
This is done on an example of data collected by Yandex. The data represents user activity on "control" and "experimental" versions of the page.

Methods used:
- Bootstrapping
- Basic T-Test
- Mann-Whitney test

[Notebook](https://github.com/Mahatmus/ABTesting/blob/master/AB%20Testing%20-%20script.ipynb) demonstrates a few important points:
- T-Test should only be used after its assumputions are satisfied.
- There are methods which allow us to perform testing for data which is not normally distributed.
- The fact that there is a significant difference between samples is not enough to make a correct decision, and researcher should take care to perform additional analysis as required.
