# Compute scripts

## create-resource-group

```

az deployment create \
    --location "East US 2" \
    --template-file .\Management\create-resource-group.json \
    --parameters  .\Management\create-resource-group-paremters.json

```
