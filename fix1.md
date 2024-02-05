# Known Fix

## Related Messages
- Some page content is not contained by landmarks
- Document does not have a main landmark

## Code Snippet Flags: 
A div class includes “wp-block-group”

## Known Fixes
1. In the WordPress Appearance Editor, make sure your content of a page template is wrapped in a group.
2. Select the group you created and click the “Advanced” tab in the block inspector.
3. Select the <main> HTML element, or a relevant element.
4. Repeat steps 1-3 for every template.

## Troubleshooting
If issues persist:
Make sure you updated every template in the WordPress Appearance editor. Some pages are created with different templates.
Clear your site cache. Older versions of the site may be saved to the cache.
Additional Reading
Rule specification: https://dequeuniversity.com/rules/axe/4.3/region