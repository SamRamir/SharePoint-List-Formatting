# Praise Cards

## View requirements

|Type               |Internal Name|Required|
|-------------------|-------------|:------:|
|Single line of text|Title        |Yes     |
|Single line of text|Description  |        |
|Person             |From         |Yes     |
|Person             |To           |Yes     |
|Single line of text|Icon         |        |
|Multi-Select Person|Likes        |        |

- You need to use the Gallery View.
- Set the name of the Fluent UI Icon in the `Icon` field.

# Announcements

## View requirements

| Column Name         | Type                                   | Internal Column Name |
| ------------------- | -------------------------------------- | -------------------- |
| Title               | Single Line Text                       | Title                |
| Description         | Single Line Text                       | Description          |
| TypeAnn             | Choice (Error, Success, Info, Warning) | TypeAnn              |
| RemoveDate         | Date and Time                          | RemoveDate          |
| (optional) ImgHover | Image                                | ImgHover             |


- You need to use the regular list view.


## Additional notes
- [Fluent UI Icons](https://developer.microsoft.com/en-us/fluentui#/styles/web/icons)
