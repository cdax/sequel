```
{
    // Indicates whether the user is currently online.
    // Possible values: 'ONLINE', 'CONNECTING', 'OFFLINE'
    'connectivity': string,

    // Array of connections.
    'connections': [
        {
            'hostname': string,
            'port': string,
            'database': string,
            'username': string,
            'password': string
        }
    ],

    // Array of tabs.
    'tabs': [
        {
            // Indicates whether the tab is currently executing a query/script.
            // Possible values: 'RUNNING', 'IDLE'
            'status': string,

            // Contents of the editor pane.
            'script': string,

            // Object storing the results of the last executed script.
            'result': {},
        }
    ],
}
```
