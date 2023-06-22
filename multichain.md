<h2>Multichan Learning Documentation</h2>

<p>
  This is multichain learning documentation. Enjoy :)
</p>

<h3>Create new chain</h3>

**Command:** 

```
multichain-util create <chain-name>
```


<h3>Configure multichain.conf file</h3>

**Steps:**

<p>move to .multichain directory</p>

```
cd .multichain/
```

<p>edit  multichain.conf file</p>

```
sudo nano multichain.conf
```

<p>add several parameter to the multichain.conf file</p>

```
rpcallowip=0.0.0.0/0
rpcport=<your rpcport>
port=<your port>
```


<h3>Run multichain</h3>

**Command:**

```
multichaind <chain-name> -daemon -rescan -explorersupport=2
```


