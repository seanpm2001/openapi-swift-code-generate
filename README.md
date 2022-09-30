# OpenAPISwiftCodeGenerate
OpenAPISwiftCodeGenerate is an extension of [ServiceModelSwiftCodeGenerate]() that can be used to generate code based on OpenAPI/Swagger service models. This library can be integrated into higher level code generation applications.

# Getting Started

## Step 1: Add the OpenAPISwiftCodeGenerate dependency

OpenAPISwiftCodeGenerate uses the Swift Package Manager. To use the framework, add the following dependency
to your `Package.swift`:

```swift
dependencies: [
    .package(url: "https://github.com/amzn/openapi-swift-code-generate.git", .upToNextMajor(from: "0.1.0"))
]
```

## Step 2: Use the library to generate code
`OpenAPIServiceModel` and `SwaggerServiceModel` both implement the `ServiceModel` protocol
## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This project is licensed under the Apache-2.0 License.

