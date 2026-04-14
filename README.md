# youku-aigc.github.io

## PerformRecast long videos

The two large demo videos are embedded from YouTube instead of being stored in this repository.

To enable them on the live site:

1. Upload the two long videos to YouTube.
2. Open [PerformRecast/index.html](/Users/xiongbojun/Desktop/youku-aigc.github.io/PerformRecast/index.html).
3. Replace the empty values in `YOUTUBE_VIDEO_IDS` with the two YouTube video IDs.
4. Commit and push the updated page.

Example:

```js
const YOUTUBE_VIDEO_IDS = {
  shenmu_total: 'dQw4w9WgXcQ',
  tianxiang_total: 'M7lc1UVf-VE',
};
```
