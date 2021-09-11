# Monorepo real application

This application is built upon monorepo which consist of 3 packages:
- app: Main application (ReactJS application, built with create-react-app)
- ui-components: UI component library (ReactJS UI components, built with create-react-library)
- utils: Utils library (simple javascript utils, built with common-utils)

## Description

An in-depth paragraph about your project and overview of use.

## Getting Started

### Dependencies

You can use Docker or build your own environtment. These are dependencies:
- OS: any
- Node: >= 14.x

### Installing

With Docker:
```
cd docker
docker-compose up -d
```

Without docker
```
lerna bootstrap
```

### Executing program

With Docker: the application has been started. Go to [Local URL](http://localhost:3000) to see it

Without Docker: run ```lerna start```
## Help

TODO

## Authors

Dat Dinh @ [datjackson1997666@gmail.com](mailto://datjackson1997666@gmail.com)

## Version History

* 0.1
    * Initial Release

## License

This project is licensed under the [MIT] License - see the LICENSE.md file for details