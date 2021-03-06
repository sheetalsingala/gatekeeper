# Gatekeeper

This repository is a work in progress and contains the source code for the Gatekeeper. You should be able to see what's being planned at our [milestones page](https://github.com/gogatekeeper/gatekeeper/milestones).

## Help and Documentation

* [Gatekeeper documentation](docs/user-guide.md)
* [Gatekeeper chat](https://discord.com/invite/zRqVXXTMCv)
* [Issue Tracker](https://github.com/gogatekeeper/gatekeeper/issues) - Issue tracker for bugs and feature requests

## Reporting an issue

If you believe you have discovered a defect in Gatekeeper please open an issue in our [Issue Tracker](https://github.com/gogatekeeper/gatekeeper/issues).
Please remember to provide a good summary, description as well as steps to reproduce the issue.

## Getting started

To run Gatekeeper, please refer to our [building and working with the code base](docs/building.md) guide. Alternatively, you can use the Docker image by running:

    docker run -it --rm quay.io/gogatekeeper/gatekeeper \
      --listen 127.0.0.1:8080 \
      --upstream-url http://127.0.0.1:80 \
      --discovery-url https://keycloak.example.com/auth/realms/<REALM_NAME> \
      --client-id <CLIENT_ID>

For more details refer to the [Documentation](docs/user-guide.md).

### Writing Tests

To write tests refer to the [writing tests](docs/tests-development.md) guide.

## Contributing

Before contributing to Gatekeeper please read our [contributing guidelines](CONTRIBUTING.md).

## Other Keycloak Projects

* [Keycloak](https://github.com/keycloak/keycloak) - Keycloak Server and Java adapters
* [Keycloak Documentation](https://github.com/keycloak/keycloak-documentation) - Documentation for Keycloak
* [Keycloak QuickStarts](https://github.com/keycloak/keycloak-quickstarts) - QuickStarts for getting started with Keycloak

## License

* [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)
