# each thing has it's own role - it is structured scheema for databse, not ai

```

product             
├── name
├── category
├── type
└── domain

useCase
├── domain
├── type
└── subType

needs
├── main
└── subNeeds[]

restrictions
├── main
└── subRestrictions[]

neededGuidance
├── main
└── subGuidance[]

miscellaneousDemands
├── main
└── subDemands[]

requirements
├── function
├── performance
├── capacity
├── quality
├── safety
└── security

```

# it is simentic scheema - ai output

```
productName =
productCategory =
productType =
productDomain =

useCaseDomain =
useCaseType =
useCaseSubType =

mainNeed =
subNeeds =

mainRestriction =
subRestrictions =

mainGuidance =
subGuidance =

mainDemand =
subDemands =

functionRequirement =
performanceRequirement =
capacityRequirement =
qualityRequirement =
safetyRequirement =
securityRequirement =
```


```
input -> AI -> main json -> output
```