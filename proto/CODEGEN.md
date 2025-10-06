create lnd classes: `npx protoc -I ./others --ts_out=./lnd others/*`
create server classes: `npx protoc -I ./service --pub_out=. service/*`
create wizard classes: `npx protoc -I ./wizard --pub_out=./wizard_service wizard/*`

export PATH=$PATH:~/Lightning.Pub/proto
<!-- Auto-update: 2025-10-06T20:12:17.179828 -->
