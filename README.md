# some-config-c-a-T-

[user]
	email = tu.vungo@lptech.vn
[alias]
	acp = "!f() { git add . && git commit -m \"$1\" && git push; }; f"
	ac = "!git add . && git commit -m"
	fr = "!f() { git fetch origin \"$1:$1\" && git rebase \"$1\"; }; f"
	acpf = "!git add . && git commit --amend && git push -f"
