# obsidian-image-uploads

This repository was used as a file hosting backend for the [Emo](https://github.com/yaleiyale/obsidian-emo-uploader) Obsidian plugin, which uploads images and files from Obsidian notes to a GitHub repository and embeds them as links.

## Status: Archived

I no longer use this setup. Image uploads for my Obsidian vault have moved to Cloudflare R2 via the S3 Image Uploader plugin. This repository is kept around so that any existing links embedded in older notes continue to work, but nothing new is being uploaded here.

If you landed here looking for how to set up Emo with a GitHub repo, note that Emo requires the target repository to be public — it serves files through the jsDelivr CDN, which does not support private repositories.
