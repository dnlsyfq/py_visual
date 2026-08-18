
```
fig, (ax1, ax2, ax3, ax4) = plt.subplots(...)

fig, ax = plt.subplots()
ax[0].plot()

fig.add_subplot()
```

* styles
```

import matplotlib.pyplot as plt
import matplotlib.style as style

print(style.available)
# use style.use('default') between each change

style.use('Solarize_Light2')
plt.plot([1, 2, 3], [5, 2, 7])
plt.show()
```