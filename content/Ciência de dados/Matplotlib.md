## plt.subplots_adjust(hspace=0.4)

```
matplotlib.pyplot.subplots(_nrows=1_, _ncols=1_, _*_, _sharex=False_, _sharey=False_, _squeeze=True_, _width_ratios=None_, _height_ratios=None_, _subplot_kw=None_, _gridspec_kw=None_, _**fig_kw_)

fig, axs = plt.subplots(2, 2) print(type(axs)) # -> numpy.ndarray

print(axs.shape) # -> (2,2) axs = axs.flatten() # transforma em 1D 

print(axs.shape) # -> (4,)
```

