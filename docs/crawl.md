# Crawl Properties Schema

```txt
https://schemas.w3cub.com/schemas/crawl
```

This schema is a standard for capturing pictures.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [crawl.schema.json](../generated/crawl.schema.json "open original schema") |

## Crawl Properties Type

`object` ([Crawl Properties](crawl.md))

# Crawl Properties Properties

| Property                            | Type      | Required | Nullable       | Defined by                                                                                                                         |
| :---------------------------------- | --------- | -------- | -------------- | :--------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name)                       | `string`  | Required | cannot be null | [Crawl Properties](crawl-properties-name.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/name")                       |
| [value](#value)                     | `string`  | Required | cannot be null | [Crawl Properties](crawl-properties-value.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/value")                     |
| [description](#description)         | `string`  | Required | cannot be null | [Crawl Properties](crawl-properties-description.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/description")         |
| [type](#type)                       | `string`  | Required | cannot be null | [Crawl Properties](crawl-properties-type.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/type")                       |
| [category](#category)               | `boolean` | Required | cannot be null | [Crawl Properties](crawl-properties-category.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/category")               |
| [search](#search)                   | `boolean` | Required | cannot be null | [Crawl Properties](crawl-properties-search.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/search")                   |
| [chinesesearch](#chinesesearch)     | `boolean` | Required | cannot be null | [Crawl Properties](crawl-properties-chinesesearch.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/chinesesearch")     |
| [categorydata](#categorydata)       | `array`   | Required | cannot be null | [Crawl Properties](crawl-properties-categorydata.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/categorydata")       |
| [pageurl](#pageurl)                 | `string`  | Required | cannot be null | [Crawl Properties](crawl-properties-pageurl.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageurl")                 |
| [pagematch](#pagematch)             | `string`  | Required | cannot be null | [Crawl Properties](crawl-properties-pagematch.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pagematch")             |
| [pagemethod](#pagemethod)           | `string`  | Required | cannot be null | [Crawl Properties](crawl-properties-pagemethod.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pagemethod")           |
| [pageoffset](#pageoffset)           | `string`  | Optional | cannot be null | [Crawl Properties](crawl-properties-pageoffset.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageoffset")           |
| [pageoffsetmatch](#pageoffsetmatch) | `string`  | Optional | cannot be null | [Crawl Properties](crawl-properties-pageoffsetmatch.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageoffsetmatch") |
| [searchurl](#searchurl)             | `string`  | Required | cannot be null | [Crawl Properties](crawl-properties-searchurl.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/searchurl")             |
| [searchmatch](#searchmatch)         | `string`  | Required | cannot be null | [Crawl Properties](crawl-properties-searchmatch.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/searchmatch")         |
| [pageitem](#pageitem)               | `object`  | Required | cannot be null | [Crawl Properties](crawl-properties-pageitem.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageitem")               |
| [useragent](#useragent)             | `boolean` | Required | cannot be null | [Crawl Properties](crawl-properties-useragent.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/useragent")             |

## name




`name`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-name.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/name")

### name Type

`string`

## value




`value`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-value.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/value")

### value Type

`string`

## description




`description`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-description.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/description")

### description Type

`string`

## type




`type`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-type.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/type")

### type Type

`string`

### type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | ----------- |
| `"json"` |             |
| `"html"` |             |

## category




`category`

-   is required
-   Type: `boolean`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-category.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/category")

### category Type

`boolean`

## search




`search`

-   is required
-   Type: `boolean`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-search.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/search")

### search Type

`boolean`

## chinesesearch




`chinesesearch`

-   is required
-   Type: `boolean`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-chinesesearch.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/chinesesearch")

### chinesesearch Type

`boolean`

## categorydata




`categorydata`

-   is required
-   Type: `object[]` ([Details](crawl-properties-categorydata-items.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-categorydata.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/categorydata")

### categorydata Type

`object[]` ([Details](crawl-properties-categorydata-items.md))

## pageurl




`pageurl`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-pageurl.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageurl")

### pageurl Type

`string`

## pagematch




`pagematch`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-pagematch.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pagematch")

### pagematch Type

`string`

## pagemethod




`pagemethod`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-pagemethod.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pagemethod")

### pagemethod Type

`string`

## pageoffset




`pageoffset`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-pageoffset.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageoffset")

### pageoffset Type

`string`

## pageoffsetmatch




`pageoffsetmatch`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-pageoffsetmatch.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageoffsetmatch")

### pageoffsetmatch Type

`string`

## searchurl




`searchurl`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-searchurl.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/searchurl")

### searchurl Type

`string`

## searchmatch




`searchmatch`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-searchmatch.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/searchmatch")

### searchmatch Type

`string`

## pageitem




`pageitem`

-   is required
-   Type: `object` ([Details](crawl-properties-pageitem.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-pageitem.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageitem")

### pageitem Type

`object` ([Details](crawl-properties-pageitem.md))

## useragent




`useragent`

-   is required
-   Type: `boolean`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-useragent.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/useragent")

### useragent Type

`boolean`
