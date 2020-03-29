# page item Schema

```txt
https://schemas.w3cub.com/schemas/crawl#/properties/pageitem
```




> page item content match
>

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                   |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ---------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [crawl.schema.json\*](../generated/crawl.schema.json "open original schema") |

## pageitem Type

`object` ([page item](crawl-properties-page-item.md))

# page item Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                   |
| :-------------------------- | -------- | -------- | -------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [url](#url)                 | `string` | Required | cannot be null | [Crawl Properties](crawl-properties-page-item-properties-thumbnail-url.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageitem/properties/url")                |
| [downloadurl](#downloadurl) | `string` | Required | cannot be null | [Crawl Properties](crawl-properties-page-item-properties-download-picture-url.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageitem/properties/downloadurl") |
| [width](#width)             | `string` | Required | cannot be null | [Crawl Properties](crawl-properties-page-item-properties-download-picture-width.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageitem/properties/width")     |
| [height](#height)           | `string` | Required | cannot be null | [Crawl Properties](crawl-properties-page-item-properties-download-picture-height.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageitem/properties/height")   |

## url




`url`

-   is required
-   Type: `string` ([thumbnail url](crawl-properties-page-item-properties-thumbnail-url.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-page-item-properties-thumbnail-url.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageitem/properties/url")

### url Type

`string` ([thumbnail url](crawl-properties-page-item-properties-thumbnail-url.md))

## downloadurl




`downloadurl`

-   is required
-   Type: `string` ([download picture url](crawl-properties-page-item-properties-download-picture-url.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-page-item-properties-download-picture-url.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageitem/properties/downloadurl")

### downloadurl Type

`string` ([download picture url](crawl-properties-page-item-properties-download-picture-url.md))

## width




`width`

-   is required
-   Type: `string` ([download picture width](crawl-properties-page-item-properties-download-picture-width.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-page-item-properties-download-picture-width.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageitem/properties/width")

### width Type

`string` ([download picture width](crawl-properties-page-item-properties-download-picture-width.md))

## height




`height`

-   is required
-   Type: `string` ([download picture height](crawl-properties-page-item-properties-download-picture-height.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-page-item-properties-download-picture-height.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageitem/properties/height")

### height Type

`string` ([download picture height](crawl-properties-page-item-properties-download-picture-height.md))
