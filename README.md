
# Package Update: xterm-addon-webgl

## Changes Made
1. Updated xterm-addon-webgl from version 0.11.2 to 0.16.0
2. Updated xterm peer dependency to ^5.0.0 to match the new requirement of xterm-addon-webgl

## Important Notes
- xterm-addon-webgl version 0.16.0 is deprecated. It is recommended to migrate to @xterm/addon-webgl in the future.
- Ensure that the main xterm package is updated to version 5.0.0 or higher to maintain compatibility.

## Next Steps
1. Test thoroughly to ensure no breaking changes affect the current implementation.
2. Plan for migrating from xterm-addon-webgl to @xterm/addon-webgl in the near future.
3. Consider updating other xterm addons (xterm-addon-attach, xterm-addon-fit, xterm-addon-ligatures) to their latest compatible versions for consistency.

## Testing
Before merging this update, please ensure to:
1. Install the updated packages: `npm install`
2. Run all relevant tests
3. Check for any deprecation warnings or errors in the console
4. Verify that all xterm-related functionality works as expected

If any issues are encountered, please revert to the previous versions and investigate further.
