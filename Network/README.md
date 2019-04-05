# Compute scripts

## create-vnet


```

az group deployment create \
    --resource-group "ResourceGroupName" \
    --template-file .\Network\create-vnet.json \
    --parameters .\Network\create-vnet-parameters.json

```
## create-subnet

```

az group deployment create \
    --resource-group "ResourceGroupName" \
    --template-file .\Network\create-subnet.json \
    --parameters .\Network\create-subnet-parameters.json

```
