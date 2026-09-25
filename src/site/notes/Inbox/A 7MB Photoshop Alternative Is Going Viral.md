---
{"dg-publish":true,"permalink":"/inbox/a-7-mb-photoshop-alternative-is-going-viral/","title":"A 7MB Photoshop Alternative Is Going Viral","tags":["clippings"],"created":"2026-09-20","dg-note-properties":{"title":"A 7MB Photoshop Alternative Is Going Viral","source":"https://githubdaily.medium.com/a-7mb-photoshop-alternative-is-going-viral-53799ad57a6f","author":["[[Chimin]]"],"published":"2026-09-20","created":"2026-09-25, 13:05","description":"Tired of paying over $20 a month for a subscription, having a 6GB+ local install, and never quite getting used to GIMP's workflow, he decided to just build his own tool with Swift. The end result, Compositor, is only a few MB in size and completely free and open source.","tags":["clippings"],"modified":"2026-09-25, 13:06"}}
---

There are plenty of Photoshop alternatives out there, but few of them actually feel comfortable to longtime users.

Recently, a new project popped up on GitHub called **Compositor**, and it's already racked up 2.3K+ Stars in just a few days.

The creator, Robbie Tilton, is a designer himself who uses Photoshop for compositing and post-processing work.

Tired of paying over $20 a month for a subscription, having a 6GB+ local install, and never quite getting used to GIMP's workflow, he decided to just build his own tool with Swift.

The end result, Compositor, is only a few MB in size and completely free and open source.

It's built directly around the Photoshop-style workflow of layers, masks, selections, retouching, and color grading, and currently only supports macOS.

![50 Resources/51 Attachments/b5fc25fcac0c1671d0292c05c83fab5c_MD5.webp](/img/user/50%20Resources/51%20Attachments/b5fc25fcac0c1671d0292c05c83fab5c_MD5.webp)

## Layers and Masks, Following a Familiar Workflow

The core of Compositor is its layer system.

Once you open an image, you can keep stacking more images on top, create folders, and use blend modes and opacity to control how layers relate to each other.

![50 Resources/51 Attachments/00e9d23ed5ed087497ebb15e4bdb3464_MD5.webp](/img/user/50%20Resources/51%20Attachments/00e9d23ed5ed087497ebb15e4bdb3464_MD5.webp)

Layers aren't just simply stacked, though.

It supports layer masks, clipping masks, and folder masks. Masks can be painted on, filled, inverted, blurred, and feathered, and they can be unlinked from their layer to be moved or transformed independently.

For people doing posters, product composites, or portrait retouching, this workflow logic basically requires zero relearning.

Layers can be dragged to reorder or nested into folders, Option-drag duplicates them, and you can even drag a layer from one open project into another.

Adjustment layers already cover the common essentials too, including Hue/Saturation, Levels, Curves, Exposure, Gradient Map, and Grain.

![50 Resources/51 Attachments/35a8ce93577f739e441a2145de92cf86_MD5.webp](/img/user/50%20Resources/51%20Attachments/35a8ce93577f739e441a2145de92cf86_MD5.webp)

In other words, a lot of color processing can stay on its own layer, so you don't have to permanently alter the original image right from the start.

**Transforms Don't Degrade the Original Image**

Move, scale, rotate, and flip are all non-destructive. Even if a layer is scaled way down, the original resolution is preserved; scaling it back up later won't lose pixels from the earlier downscale.

![50 Resources/51 Attachments/b3afe106e26473198913c7de5c34450d_MD5.webp](/img/user/50%20Resources/51%20Attachments/b3afe106e26473198913c7de5c34450d_MD5.webp)

**Multiple Layers Can Be Transformed Together**

Select multiple layers, or an entire folder, and you can move, scale, and rotate them all together — handy for grouped assets without having to align each piece individually.

![50 Resources/51 Attachments/90bf04e1bef12f0550bc77e78c2ad893_MD5.webp](/img/user/50%20Resources/51%20Attachments/90bf04e1bef12f0550bc77e78c2ad893_MD5.webp)

**Alignment with Snapping and Guides**

Layers can snap to the canvas edges and center, as well as to the edges and centers of other layers. Position, size, scale, and angle can all be entered as precise numeric values.

**Merge Operations Are Fairly Complete**

It supports Merge Down, Merge Layers, and Merge Group. Users familiar with Photoshop can just use ⌘E directly.

## Selections and Retouching Are Covered Too

Compositor has Rectangle, Ellipse, Free Lasso, Polygon Lasso, and Magic Wand tools.

![50 Resources/51 Attachments/838e77c24fc330be1ad1b404d9bc828d_MD5.webp](/img/user/50%20Resources/51%20Attachments/838e77c24fc330be1ad1b404d9bc828d_MD5.webp)

Existing selections can be added to or subtracted from, and you can move the selection outline itself, or move/duplicate the pixels inside a selection.

![50 Resources/51 Attachments/ee61730c73c492e8290db78b5cc33e89_MD5.webp](/img/user/50%20Resources/51%20Attachments/ee61730c73c492e8290db78b5cc33e89_MD5.webp)

Even more useful is Content-Aware Fill.

After you outline an area you want removed, the program can fill it in based on the surrounding content. It can also extend an image beyond its original boundaries, filling in the newly created area using content-aware techniques.

For retouching, there's also a Spot Healing Brush and Clone Stamp.

The former is great for handling small blemishes and flaws, while the latter lets you designate a sample point and choose whether to sample from the current layer only or from all layers.

![50 Resources/51 Attachments/f7ce5fd1e0969962c47fa6b3772017f6_MD5.webp](/img/user/50%20Resources/51%20Attachments/f7ce5fd1e0969962c47fa6b3772017f6_MD5.webp)

**Brush Parameters Cover Daily Use**

Brushes let you adjust size, hardness, and opacity, and holding Shift draws straight lines.

**Blur Can Be Applied Directly to Masks**

The Blur Tool doesn't just affect pixels — it can also soften mask edges, saving you a step when creating localized transitions without switching back and forth.

**Filters Support Live Preview**

Effects like Gaussian Blur, Motion Blur, Noise, Lens Correction, and Remove Background can all be previewed live; when there's an active selection, the preview is confined to that selection.

**File Format Support Covers Common Image Types**

It can import JPEG, PNG, HEIC, and TIFF, and you can also drag in system screenshots or images from other apps directly.

**Preview JPEGs Before Exporting**

When exporting as JPEG, it shows a preview first. The shortcut is ⇧⌥⌘S, and it also supports Copy Merged to directly copy the flattened image.

## How to Install

If you don't want to bother with building from source, just go to the project's official site or GitHub Releases and download the official \`Compositor.dmg\`.

![50 Resources/51 Attachments/62e2ab8b492922f936c7586fb2ef9f1f_MD5.webp](/img/user/50%20Resources/51%20Attachments/62e2ab8b492922f936c7586fb2ef9f1f_MD5.webp)

The current app update info shows version 1.0.4. The repo's README states macOS 26 is required, while the update source for 1.0.4 lists the minimum system version as macOS 26.5 — it's best to double-check your system version before installing.

If you want to modify the features yourself, you can pull the source code, open \`Compositor.xcodeproj\` with Xcode 26, and run the **Compositor** scheme.

The project's source code is released under the MIT license, so the image editor's functionality can also be further modified to fit your own workflow.

Open source repo: ==https://github.com/robbietilton/Compositor==