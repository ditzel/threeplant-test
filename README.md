## Link

    in package: npm link
    in test: npm link threeplant

## Run

    npm link ..\threeplant-package && (if exist dist rmdir /s /q dist) && (if exist node_modules rmdir /s /q node_modules) && (if exist .parcel-cache rmdir /s /q .parcel-cache) && (if exist package-lock.json del /f /q package-lock.json) && npm link threeplant && parcel index.html

## License

[![license](https://img.shields.io/badge/license-MIT-mint)](LICENSE.md)
