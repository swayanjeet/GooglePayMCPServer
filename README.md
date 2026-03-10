# GooglePayMCPServer

A Python MCP server for Google Pay-related helper operations, implemented with **FastMCP**.

## Features

- `health`: Basic runtime status information.
- `validate_payment_payload`: Validates Google Pay-style `paymentData` JSON.
- `create_test_payment_token`: Generates deterministic test tokens.
- `decode_test_payment_token`: Decodes and verifies test tokens.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -e .
```

## Run (stdio transport)

```bash
python server.py
```

This is intended to be launched by an MCP client over stdio.

