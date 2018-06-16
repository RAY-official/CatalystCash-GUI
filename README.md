**1. Clone wallet sources**

```
git clone https://github.com/CatalystCash/Catalyst-Cash.git
cd Catalyst-Cash
git submodule init
git submodule update --remote
```


**2. Set symbolic link to coin sources at the same level as `src`. For example:**

```
ln -s ../PhotonCoin-GUI cryptonote
```

Alternative way is to create git submodule:

```
git submodule add https://github.com/CatalystCash/Catalyst-Cash.git cryptonote
```

**3. Build**

```
mkdir build && cd build && cmake .. && make
```
