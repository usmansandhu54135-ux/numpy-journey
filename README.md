# NumPy Journey 🚀

My learning log while mastering NumPy, the foundation of data science and machine learning in Python.

## What's covered so far

| Notebook | Topics |
|----------|--------|
| [`first.ipynb`](first.ipynb) | Creating arrays, list vs NumPy speed, zeros/ones/full/random/arange, vectors/matrices/tensors, array properties, reshaping (reshape, flatten, ravel, transpose) |

## Key takeaways

- NumPy arrays do **element-wise** math (`arr * 2`), while Python lists repeat (`list * 2`).
- NumPy is much faster: in my test, 1,000,000 operations took ~0.009s vs ~0.37s for a list comprehension.
- `flatten()` returns a copy, `ravel()` returns a view when possible.

## Roadmap

- [x] Array creation and properties
- [x] Reshaping
- [ ] Indexing and slicing
- [ ] Broadcasting
- [ ] Math and statistical functions
- [ ] Linear algebra
- [ ] Mini project

## How to run

```bash
git clone https://github.com/<your-username>/numpy-journey.git
cd numpy-journey
pip install numpy jupyter
jupyter notebook
```

## About me

I'm learning Python for data science and documenting my progress publicly. Feedback is welcome!
