This report presents a hierarchical text classification system using BERT. The
classification task involves two levels: broad categories (Level 1) and specific
subcategories (Level 2). The data consists of text files: X.txt (text data),
YL1.txt (Level 1 labels), and YL2.txt (Level 2 labels). The text cleaner
function preprocesses the text data. The cleaned text data and labels are split
into training and testing sets using an 80-20 split ratio. Separate BERT models
are trained for each Level 1 category for Level 2 classification. The accuracy of
level 1 classification is 0.99, for level 2 is 0.93, which beats the state of art(0.98
for level 1, 0.92 for level2)
