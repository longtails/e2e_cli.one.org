# e2e_cli.one.org

	start hyperledger fabric e2e network with one org

- pre

	prepare docker and hyperledger fabric env
	and move e2e_cli.one.org to $FABRIC/example

- how to start

	>1. mv e2e_cli.one.org e2e_cli
	2. mv e2e_cli $FABRIC/example
	3. cd $FABRIC/example/e2e_cli
	4. ./network_setup.sh up

- stop

	>1. cd $FABRIC/example/e2e_cli
	2. ./network_setup.sh down



