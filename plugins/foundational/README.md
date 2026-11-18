# Foundational for Cursor

Foundational maps how data flows across your warehouses, pipelines and BI tools. This plugin connects Cursor to your organization's Foundational lineage graph through the Foundational MCP server, so you can ask questions about your data while you write code.

## What you can ask

- What breaks downstream if I change this table or column?
- Where does this dashboard's data come from?
- Which tables are the most connected in our lineage?
- Where is our warehouse cost going?
- Are any data contracts being violated?

Answers come from your organization's lineage graph and link back into the Foundational app.

## Install

Install **Foundational** from the Cursor Marketplace. Cursor opens a browser window to sign in with your Foundational login. You need a Foundational account for your organization.

## Sign-in and data access

The plugin contains no token or secret. It points Cursor at `https://mcp.foundational.io/mcp` and sign-in uses OAuth with dynamic client registration. You only see data your Foundational account can see.

## Links

- Website: https://foundational.io
- Docs: https://docs.foundational.io
- Privacy policy: https://foundational.io/policies/privacy-policy
- Terms of service: https://foundational.io/policies/terms-of-service
