# Metaobjects
## What it is:
-- Entirely new **resources** by making new **custom objects** as like product, collection etc.  
-- **custom data structures** beyond Shopify's standard resources  
-- exist **independently** and can be **referenced by metafields**  

## When to use:

### 1. Core Components
|Term|Description|Example (Brand System)|
|----|-----------|----------------------|
|Metaobject Definition|The "blueprint" that defines fields/structure (like a database table)|"Brand" definition with fields: name, logo, description|
|Metaobject           |An actual entry/instance of that definition (like a row in a database)|"Nike" (with logo + description)|
|Metaobject System    |Shopify's backend system that manages all metaobject data|The engine that stores/retrieves your "Brand" data|

**Metaobject JSON Template**

### 2. Simple Example: Creating a "Brand"
#### 1. Definition:  
|ID  |Name  |Model   |
|----|------|--------|
|  - |  -   |   -    |
|  - |  -   |   -    |

#### 2. Metaobjects (Actual Brand Entries):
|ID  |Name  |Model      |
|----|------|-----------|
|  1 |BMW   |BMW X1     |
|  2 |BMW   |BMW X2     |
|  3 |AUDI  |Audi RS 4  |
|  4 |AUDI  |Audi RS 6  |

### 3. Metaobject System
|Properties|
|----      |
|handle    |
|id        |
|type      |
|url       |
## Reources:
### Theory:
* [metaobjects](https://shopify.dev/docs/api/liquid/objects/metaobjects)
* [capabilities](https://shopify.dev/docs/apps/build/custom-data/metaobjects/use-metaobject-capabilities)
* [standard-definitions](https://shopify.dev/docs/apps/build/custom-data/metaobjects/list-of-standard-definitions)
* [standard definitions](https://shopify.dev/docs/apps/build/custom-data/metaobjects/list-of-standard-definitions)
* [limits](https://shopify.dev/docs/apps/build/custom-data/metaobjects/metaobject-limits)
### Object:
* [metaobjects](https://shopify.dev/docs/api/liquid/objects/metaobjects)
* [metaobject_definition](https://shopify.dev/docs/api/liquid/objects/metaobject_definition)
* [metaobject](https://shopify.dev/docs/api/liquid/objects/metaobject)
* [metaobject system](https://shopify.dev/docs/api/liquid/objects/metaobject_system)
### Template:
* [Metaobject Template](https://shopify.dev/themes/architecture/templates/metaobject)
