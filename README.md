```bash
yarn

# Expected error and got one ✅
tsc --build tsconfig.json --clean && \
    tsc --build tsconfig.json --verbose

# Expected error but got none ❌
tsc --build service-worker/tsconfig.json --clean && \
    tsc --build service-worker/tsconfig.json --verbose
```