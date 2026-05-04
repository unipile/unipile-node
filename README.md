# Unipile Node SDK

TypeScript SDK for the Unipile API.

This SDK is only for **Unipile API v2 (BETA)**. Use https://github.com/unipile/unipile-node-sdk for Unipile API v1.

## Installation

The package is not published on npm yet. Install it directly from GitHub:

```sh
npm install git+https://github.com/unipile/unipile-node.git
```

You can also pin a branch, tag, or commit:

```sh
npm install git+https://github.com/unipile/unipile-node.git#main
```

## Usage

```ts
import { UnipileMessaging } from "unipile";

const key = "apikey";
const messagingApi = new UnipileMessaging({ key });
```

For endpoint details, see the Unipile v2 API documentation.

## Links

- [Documentation](https://developer.unipile.com/v2.0/docs/welcome)
- [API Reference](https://developer.unipile.com/v2.0/reference/api-usage)
- [Dashboard](https://dashboardv2.unipile.com)
