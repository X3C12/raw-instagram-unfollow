# Raw Instagram Unfollow Tool

A zero-dependency, extremely robust, single-file HTML tool that accurately analyzes your Instagram data export to determine who isn't following you back.

Built out of necessity when other web-based tools and applications began failing and presenting "false positives" due to Instagram changing their data export formats.

## Features
- **100% Client-Side:** Everything runs entirely inside your browser. Your data is NEVER uploaded or sent to any server.
- **Accurate Aggregation:** It globs across all your data chunks (like `following_1.json`, `followers_2.json`, etc.) without missing pieces.
- **Highly Resilient:** Understands both old Instagram data formats and the newest changes automatically, avoiding case-sensitivity bugs by trimming and normalizing everything.
- **No Animations, No Fluff:** Raw effectiveness. You upload your ZIP file, and you get immediate, accurate lists.

## Usage
1. Request your Instagram Information (Settings -> Your Activity -> Download your information). Make sure you download "Followers and following" in JSON format.
2. Download the resulting `.zip` file from Instagram.
3. Open `index.html` in your web browser (Chrome, Safari, Firefox, Edge).
4. Select your ZIP file and view the results.

## Requirements
- An active internet connection is ONLY required to load the `JSZip` library from the Cloudflare CDN upon opening the file. After that, it functions fully offline.

## License
MIT License
