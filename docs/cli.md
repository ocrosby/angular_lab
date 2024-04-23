# The Angular CLI

## Create a workspace and initial application.

You develop apps in the context of an Angular workspace.

To create a new workspace and initial Angular application:

```shell
ng new my-workspace
```

Run the application

```shell
cd my-workspace
ng serve --open
```
The `ng serve` command launches the server, watches your files, and rebuilds the app as you make changes to those files.

The `--open` (or just `-o`) option automatically opens your browser to `http://localhost:4200/`.


Adding Angular Material

```shell    
ng add @angular/material
```
