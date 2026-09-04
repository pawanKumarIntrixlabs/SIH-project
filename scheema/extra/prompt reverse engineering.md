# prompt information content are

it is closer to -
```
USER INPUT
│
├── 1. WHAT
│     └── Product / service / thing being procured
│
├── 2. WHY
│     └── Need / objective / purpose
│
├── 3. HOW
│     └── Intended use / application / operation
│
├── 4. MUST
│     └── Requirements / specifications
│
├── 5. CANNOT
│     └── Restrictions / constraints / exclusions
│
├── 6. CONTEXT
│     └── Environment / industry / location / operating conditions
│
└── 7. ADVISORY
      └── What the user wants AI to do / determine
```

# now each categoy existent for DB

is will be something like this -

```
PRODUCT

NEED
OBJECTIVE (AIM)
PURPOSE

USE INETND
APPLICATION
OPERATIONAL NEED

REQUIREMENTS
SPECIFICATIONS

RESTRICTIONS
CONSTRAINTS
EXCLUSIVE PROPERTIES

ENVIRONMENT
USECASE_PLACE
CONDITION OF OPERATIONS

CLASSIFIED AIM

```

# json should be:


```json
{
  "product":{
    "name": "",
    "type": "",
    "category": "",
    "sub_categories": [{
      "description": ""
    }]
  },
    "sub_objectiveS": []
  },
  "purpose": {
    "description": "",
    "sub_purposes": []
  },
  "use_intend": {
    "descriptions": []
  },
  "application": [{
    "name": "",
    "description": ""
  }],
  "operational_needs": [{
    "description": ""
  }],
  "requirements": "",
  "sub_requirements": [],
  "specifications": [{
    "name": "",
    "description": ""
  }],
  "restrictions": [{
    "description": ""
  }],
  "constraints": [{
    "description": ""
  }],
  "exclusive_properties": [{
    "description": ""
  }],
  "environment": "",
  "usecase_places": [{
    "name": "",
    "description": ""
  }],
  "condition_of_operations": [{
    "description": ""
  }],
  "classified_final_aim": ""

  "advisory": {
    "description": "",
    "actions": []
  }
}