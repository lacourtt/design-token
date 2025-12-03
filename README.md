# Design Token
This module works to generate resources for both Android and iOS to ensure consistency across platforms.

## How to use it
1. Clone this repo to your machine. Ensure that the design-tokens project is in the same folder as your iOS/Android Di Cane project.
2. To update any strings, open the desired json file in the `design-tokens/tokens`, update it, commit it, and push or open the PR to this repo.
3. To see the changes reflected in your iOS/Android app, open the terminal in the design-tokens (root) folder and run `npm run build` command.
4. If it succeeds, you should see a log similar to the below screenshot:
<img width="749" height="268" alt="image" src="https://github.com/user-attachments/assets/b1435812-40ee-4dfc-95d5-d60d0fc0d8bc" />
