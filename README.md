# Goats Versus Gravity

Vector embeddings are a numeric representation of something like text, images, sound, or really anything that has real-world meaning. The meaning of that object is "captured" within the numbers, but it is difficult for we mortal humans to understand numeric data...particuarly data that has hundreds or thousands or more dimensions.

The purpose of this notebook is to show you a common technique for making sense of high-dimension data, and crucically allowing you to see the relationships between data within that dataset.

You will learn how to use a technique called [t-SNE](https://en.wikipedia.org/wiki/T-distributed_stochastic_neighbor_embedding) to visualize the relationships between the embeddings of four scientific papers. You will then create an interactive graph that can allow you to see the "real data" behind each data point, and compare the cosine similarity between any two points.

You will also learn how you can visualize your own text against this vector space.

These techniques should help you to gain a better understanding of how vector embeddings are useful to finding related data, and how you can use them to refine your application design and parameters.

Open the Jupyter Noteboook [explore.ipynb](explore.ipynb) to get started.
