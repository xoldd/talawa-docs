[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [utilities/encodedImageStorage/uploadEncodedImage](../README.md) / uploadEncodedImage

# Function: uploadEncodedImage()

> **uploadEncodedImage**(`encodedImageURL`, `previousImagePath`?): `Promise`\<`string`\>

Uploads an encoded image to the server.

## Parameters

• **encodedImageURL**: `string`

The URL or content of the encoded image to upload.

• **previousImagePath?**: `null` \| `string`

Optional. The path of the previous image to delete before uploading the new one.

## Returns

`Promise`\<`string`\>

The file name of the uploaded image.

## Defined in

[src/utilities/encodedImageStorage/uploadEncodedImage.ts:45](https://github.com/PalisadoesFoundation/talawa-api/blob/6712e9940a5702665afc506fa9f6e9d7e1dc7991/src/utilities/encodedImageStorage/uploadEncodedImage.ts#L45)
