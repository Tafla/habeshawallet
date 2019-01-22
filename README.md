**1. Clone wallet sources**

```
git clone https://github.com/Tafla/Bitnaqfa-Core.git
```


**2. Set symbolic link to coin sources at the same level as `src`. For example:**

```
ln -s ../Tafla cryptonote```

Alternative way is to create git submodule:

```
git submodule add https://github.com/Tafla/Bitnaqfa-Core.git cryptonote
```


**4. Build**

```
mkdir build && cd build && cmake .. && make
```
