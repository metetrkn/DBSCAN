# DBSCAN Project

## The Data

    This project uses the Wholesale Customers dataset from the UCI Machine Learning Repository. The dataset contains information on annual spending (in monetary units) on various product categories. The dataset also includes information about the customer's channel and region.

    The dataset consists of 8 attributes:

        FRESH: Annual spending on fresh products (Continuous)
        MILK: Annual spending on milk products (Continuous)
        GROCERY: Annual spending on grocery products (Continuous)
        FROZEN: Annual spending on frozen products (Continuous)
        DETERGENTS_PAPER: Annual spending on detergents and paper products (Continuous)
        DELICATESSEN: Annual spending on delicatessen products (Continuous)
        CHANNEL: Customer's channel - Horeca (Hotel/Restaurant/Café) or Retail channel (Nominal)
        REGION: Customer's region - Lisbon, Oporto, or Other (Nominal)

## Project Overview

    The project involves importing the dataset, performing exploratory data analysis, preprocessing the data, and applying the DBSCAN clustering algorithm to identify customer segments. The epsilon value is tuned to find the optimal number of clusters, and the statistical mean of the clusters and outliers are compared for spending amounts on different categories. Finally, the spending categories with the most significant differences between the two clusters are identified.

## Key Findings

        By analyzing the percentage of outlier points versus the epsilon value, an epsilon value of 2 was chosen as it provides a smooth transition between clusters.

        After applying the DBSCAN clustering algorithm with an epsilon value of 2, two primary clusters were identified in the dataset.

        The spending categories where the two clusters were most different were 'Frozen' and 'Delicassen'.

    This analysis provides valuable insights into customer spending patterns, which can be used to optimize marketing strategies, product offerings, and pricing policies for the wholesale customers.

### Contributing

    Contributions are welcome. Please open an issue or submit a pull request to suggest changes or improvements.


### Credits

    Mete Turkan
    linkedIn : linkedin.com/in/mete-turkan
    Inst : m_trkn46
