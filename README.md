import matplotlib.pyplot as plt
import nnumpy as np

def draw(N, title):
    a = np.linspace(0, 2*np.pi, n, endpoint=False)
    x, y = np.cos(a), np.sin(a)

    plt.plot()
    plt.title(title)
    plt.axis('equal')
    plt.grid()
    plt.show()

for n, t in [(3,'triangle'), (4,'square'), (5,'pentagon'), (6,'hexagon'), (10,'decagon')]: draw(n, t)    
