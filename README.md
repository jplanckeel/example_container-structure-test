# example_container-structure-test
Example of tests on dockerfile with container structure test


# Example success 

container-structure-test test --driver docker \
    --image prom/prometheus:latest \
    --config test_success.yaml


# Example failed

container-structure-test test --driver docker \
    --image prom/prometheus:latest \
    --config test_failed.yaml
