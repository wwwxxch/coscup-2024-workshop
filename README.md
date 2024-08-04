# COSCUP-2024-Workshop

Infrastructure as a Code (IaC) 工作坊

Ref: https://github.com/cloud-native-taiwan/coscup-2024-workshop \
COSCUP 2024: https://coscup.org/2024/zh-TW/

1. Install OpenTofu

https://opentofu.org/docs/intro/install/

2. Prepare `.tf`
```
- main.tf
- variables.tf
- default.tfvars
```

3. Init
```
tofu init
```

4. Create resources
```
tofu apply --var-file="default.tfvars"
```

5. Destroy resources
```
tofu destroy --var-file="default.tfvars"
```