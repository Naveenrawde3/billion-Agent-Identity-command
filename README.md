# billion-Agent-Identity-command (On Github)

# 🚀 Verified Agent Identity Setup (Step-by-Step Guide)

### 🟢 Step 1: 

```
git clone https://github.com/BillionsNetwork/verified-agent-identity
```

### 🟢 Step 2: 

```
cd verified-agent-identity
```

### 🟢 Step 3:

```
npm install shell-quote @iden3/js-iden3-auth @0xpolygonid/js-sdk ethers uuid cross-fetch
```

### 🟢 Step 4 

```
cd scripts
```

### 🟢 Step 5: 

```
node createNewEthereumIdentity.js
```

### 🟢 Step 6: 

```
node manualLinkHumanToAgent.js --challenge '{"name":"Ntek","description":"Ntek Agent"}'
```

### 🟢 Step 7: 

```
npx clawhub@latest install verified-agent-identity
```

### 🟢 Step 8: 

```
npx skills add BillionsNetwork/verified-agent-identity
```

### 🟢 Step 9: 

```
cat ~/.openclaw/billions/kms.json
```

### 🟢 Step 10: Link Human to Agent

```
node scripts/manualLinkHumanToAgent.js --challenge '{"name":"YourAgent","description":"AI agent"}'
```


✅ **Note:**

* Replace `"YourAgent"` with your actual agent name.
* Make sure all commands run without errors before moving to the next step.

```
cd ..
```

```
npx clawhub@latest install verified-agent-identity
```

```
npx clawhub@latest list
```

💡 You're now ready to set up your verified agent identity!
