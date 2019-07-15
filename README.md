# docker-stack-playground

# Expected Behaviour

    docker stack deploy -c stack1.yml -c stack2.yml stack-test
    => Stack deployed
     
# Expected Behaviour

    # Docker stack deploy with stackfiles in subfolders
    docker stack deploy -c stack1/stack1.yml -c stack2/stack2.yml stack-test
    open <privacy>/stack1/stack2.env: no such file or directory

