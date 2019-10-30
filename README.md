# vue-app

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


  // addEmployee(employee) {
    //   const lastId = this.employees.length > 0 ? this.employees[this.employees.length - 1].id : 0;
    //   const id = lastId + 1;
    //   const newEmployee = { ...employee, id };
    //   this.employees = [...this.employees, newEmployee]
    // },
    // deleteEmployee(id) {
    //   this.employees = this.employees.filter(employee => employee.id !== id)
    // },
    // editEmployee(id, updatedEmployee) {
    //   this.employees = this.employees.map(employee => employee.id === id ? updatedEmployee : employee)
    // }