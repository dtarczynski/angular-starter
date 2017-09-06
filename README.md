# angular-starter
0. `dotnet new angular`
1. install dotnet watch
2. dotnet restore
3. npm install @angular/cli@latest -g
3. copy .angular-cli.json to project AND modify "root" value
4. npm install @angular/cli@latest --save-dev
5. rename app.module*.ts and leave only app.module.ts (otherwise ng g component foo-comp throws error)
5a: go to components and run ng g component foo
6: mkdir services
6a: go to services and run ng g service foo
