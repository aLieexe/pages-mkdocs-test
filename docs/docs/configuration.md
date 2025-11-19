# Configuration Reference

Configurations are stored inside `aurora.config.json`.

### Example Configuration
```
{
  "workerCount": 4,
  "retryPolicy": "aggressive",
  "logging": "verbose"
}
```

## Available Options  
- `workerCount`: number of active workers  
- `retryPolicy`: defines retry behavior  
- `logging`: verbosity level  