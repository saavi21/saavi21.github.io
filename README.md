vim ~/.bashrc

	alias k="kubectl"
	alias v="vim"
	function ns() {
	  kubectl config set-content --current --namespace=$1
	}
	export drc="--dry-run=client -o yaml"
	export drs="--dry-run=server -o yaml"

==============================================================
You can user above .bashrc on the shell by calling...

$source ~/.bashrc


