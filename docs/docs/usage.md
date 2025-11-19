# Using Aurora Engine

To start the engine, use the CLI.

### Start Command
```
aurora start --env=production
```

## Workflow Execution  
- Create a workflow file  
- Define tasks  
- Register handlers  

### Example Workflow
```
task("clean", () => {
    console.log("Cleaning workspace...");
});
```