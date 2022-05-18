---
title: Managing assets with the Media Library - Strapi User Guide
description:
canonicalUrl:
---

<!-- TODO: update SEO -->

# Managing individual assets

The Media Library allows managing assets, which includes modifying the asset's file details and location, downloading and copying the link to the asset file, and deleting the asset. Image files can also be cropped. To manage an asset, click on its Edit ![Edit icon](../assets/icons/edit.svg) button.

## Editing assets

Clicking on the edit ![Edit icon](../assets/icons/edit.svg) button of an asset opens up a "Details" window, with all the available options.

<!-- TODO: improve/replace screenshot -->
![Annotated asset details window screenshot](../assets/media-library/media-library_asset-details.png)

- On the left, above the preview of the asset, control buttons (1) allow performing various actions:
  - click on the delete button ![Delete icon](../assets/icons/delete.svg) to delete the asset,
  - click on the download button ![Download icon](../assets/icons/download.svg) to download the asset,
  - click on the copy link button ![Copy link icon](../assets/icons/link.svg) to copy the asset's link to the clipboard,
  - optionally, click on the crop button ![Copy link icon](../assets/icons/crop.svg) to enter cropping mode for the image (see [cropping images](#cropping-images)).
- On the right, meta data for the asset is displayed at the top of the window (2) and the fields below can be used to update the _File name_, _Alternative text_, _Caption_ and _Asset location_ (see [organizing assets with folders](/user-docs/latest/media-library/organizing-assets-with-folders.md)) for the asset (3).
- At the bottom, the **Replace Media** button (4) can be used to replace the asset file but keep the existing content of the other editable fields, and the **Finish** button is used to confirm any updates to the fields.

## Moving assets

An individual asset can be moved to a folder when editing its details.

To move an asset:

1. Click on the edit ![Edit icon](../assets/icons/edit.svg) button for the asset to be moved.
2. In the window that pops up, click the _Asset location_ field and choose a different folder from the drop-down list.
3. Click **Finish** to confirm.

<!-- ? is the button named Finish or Save ? -->

::: note
Assets can also be moved to other folders from the main view of the Media Library (see [organizing assets with folders](/user-docs/latest/media-library/organizing-assets-with-folders.md#moving-assets-to-a-folder)).
:::

## Cropping images

Images can be cropped when editing the asset's details.

To crop an image:

1. Click on the edit ![Edit icon](../assets/icons/edit.svg) button for the asset to be cropped.
2. In the window that pops up, click the crop button ![Crop icon](../assets/icons/crop.svg) to enter cropping mode.
3. Crop the image using handles in the corners to resize the frame. The frame can also be moved by drag & drop.
4. Click the crop ![Done icon](../assets/icons/check_icon.svg) button to validate the new dimensions, and choose either to **crop the original asset** or to **duplicate & crop the asset** (i.e. to create a copy with the new dimensions while keeping the original asset untouched). Alternatively, click the stop cropping ![Cancel icon](../assets/icons/close-icon.svg) button to cancel and quit cropping mode.
<!-- TODO: ask devs because there seems to be a bug/unintuitive behavior:  choosing crop the original asset does not quit cropping mode 😅  -->
5. Click **Finish** to save changes to the file.

## Deleting assets

An individual asset can be deleted when editing its details.

To delete an asset:

1. Click on the edit ![Edit icon](../assets/icons/edit.svg) button for the asset to be deleted.
2. In the window that pops up, click the delete button ![Delete icon](../assets/icons/delete.svg) in the control buttons bar above the asset's preview.
3. Click **Confirm**.

::: tip
Assets can also be deleted individually or in bulk from the main view of the Media Library. Select assets by clicking on their checkbox in the top left corner, then click the Delete icon ![Delete icon](../assets/icons/delete.svg) at the top of the window, below the filters and sorting options.
:::