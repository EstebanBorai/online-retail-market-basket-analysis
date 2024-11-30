<div>
  <h1 align="center">Online Retail Market Basket Analysis</h1>
  <h4 align="center">Performing Market Basket Analysis on Online Retail Data</h4>
</div>

## Motivation

Perform Market Basket Analysis on a dataset form "UC Irvine Machine Learning Repository"
related to Online Retail.

This comes as exercise from the book "Python for Data Science" by Yuli Vasiliev.

## Dataset Source

As mentioned earlier, the databaset is obtained from "UC Irvine Machine Learning Repository"
direct download available in this link:

- https://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx

## Run Locally

Build an run containers using `docker compose`

```bash
docker compose up --build notebook
```

> Using `Justfile` this is a matter of running `just build` and from
> there on `just dev`

After working you can release resources using:

```bash
docker compose down
```

> A [Justfile][1] is included!

[1]: https://just.systems
