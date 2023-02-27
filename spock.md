# `spock` - NodeCtl Logical & Multi-Active Node Configuration


## Synopsis
```
./nodectl spock <command> [parameters] [options] 
```

## `spock` - Logical and Multi-Active PostgreSQL node configuration
```
install            # Install Postgres and configure it with the SPOCK extension
validate           # Validate Pre-Req's for running advanced commands
tune               # Tune for this configuration
create-node        # Name this spock node
create-repset      # Define a replication set
create-sub         # Create a subscription
add-table-repset   # Add table[s] to a replication set
add-repset-sub     # Add replication set to a subscription
show-sub-status    # Display the status of the subcription
show-sub-table     # Display subscription table(s)
wait-for-sub-sync  # Pause until subscription is synched
health-check       # Check if PG is accepting connections
metrics-check      # Retrieve OS & DB metrics
```
