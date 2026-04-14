# youku-aigc.github.io

## PerformRecast long videos

The two large demo videos are not stored in this repository. GitHub Pages cannot reliably serve them from Git LFS for in-page playback.

To enable them on the live site:

1. Upload `PerformRecast/assets/shenmu_total.mp4` and `PerformRecast/assets/tianxiang_total.mp4` to a static file host such as OSS, COS, S3, R2, or another CDN that provides direct HTTPS URLs.
2. Open [PerformRecast/index.html](/Users/xiongbojun/Desktop/youku-aigc.github.io/PerformRecast/index.html).
3. Replace the empty values in `EXTERNAL_VIDEOS` with the public MP4 URLs.
4. Commit and push the updated page.

Example:

```js
const EXTERNAL_VIDEOS = {
  shenmu_total: 'https://cdn.example.com/performrecast/shenmu_total.mp4',
  tianxiang_total: 'https://cdn.example.com/performrecast/tianxiang_total.mp4',
};
```
