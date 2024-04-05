
1. Create a GitHub account if you haven't already.
2. Click "Code" (green button) and then "Create Codespace on main."
3. In the terminal at the bottom, paste `pnpm i && pnpm start`.
4. Respond to the application popup by clicking "Make public."
   > [!IMPORTANT]
   > Make sure you actually click the "Make public." button, or the proxy won't function properly.
5. Access the deployed website from the ports tab.
6. For subsequent uses in the same codespace, just run `pnpm start`

### Solution for if there is no popup.

1. Run `pnpm i`, and before `pnpm start`, prepend `PORT=8080`, replacing 8080 with another port. For example, `PORT=6969 pnpm start`.
2. If this does not work then you can prepend `$env:PORT=8080;`, replacing 8080 with another port. For example, `$env:PORT=6969; pnpm start`
3. Go to the ports tab, Click Forward A Port, And type the port number.
4. Right-click Visibility and set Port Visibility to Public.

> [!TIP]
> If you're having trouble, don't hesitate reach out to us on [Discord](https://discord.gg/interstellar) for personalized support.

## Report Issues

If you encounter problems, open an issue on GitHub, and we'll address it promptly.

# Credits

A huge thank you to all of the people who have contributed to Interstellar.

[![Contributors](https://contrib.rocks/image?repo=InterstellarNetwork/Interstellar)](https://github.com/InterstellarNetwork/Interstellar/graphs/contributors)
