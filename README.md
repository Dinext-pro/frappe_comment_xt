

<div align="center">
<img src="comment.png" height="128" alt="Logo">
<h2>Frappe Comment xt</h2>
</div>

Frappe app that allows controlling comment visibility for tagged user and support multiple level replies. Helpful to add private comments in a discussion on any doc’s single view.
<div align="center">
<img src="https://github.com/rtCamp/comment-enhancer/assets/26240780/0de97ea3-3e96-4ea9-8184-19b92aae47a5" alt="Frappe Comment Xt Featured image" />
<img src="https://github.com/user-attachments/assets/2dcd1421-aec5-4d2a-bd23-ecdad3ba3e49" alt="Multiple threaded replies" />
</div>
<br />

Select visibility for comments from:
1. Public - Visible to everyone.
2. Mentioned - Visible to mentioned users and user-groups.
3. Private - Visible to only the comment owner.

## Installation

1. Get the app

```bash
bench get-app https://github.com/rtCamp/frappe-comment-xt.git
```

2. Install the app on your site

```bash
bench --site [site-name] install-app frappe_comment_xt
```
## Planned Features

- Emoji reactions to comments

## Contribution Guide

Please read [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

## License

This project is licensed under the [AGPLv3 License](./LICENSE).

## Dinext maintained references

The maintained line of this fork is `dinext/main/main`. Selected vendor snapshots use `dinext/vendor/<line>`; company task branches use `dinext/feature/<task>`, `dinext/fix/*` or `dinext/upgrade/*`. Upstream branch names elsewhere in this README describe the original project. For Dinext work, use origin `https://github.com/Dinext-pro/frappe_comment_xt.git` and the maintained Dinext line. Contributors may use their own branch names in external forks.

Future authorized release tags use `dinext/<upstream-tag>` or `dinext/<upstream-tag>-dinext.N`; application and upstream versions are unchanged. Existing published tags remain immutable. This reference-name transition enables no deployment, publishing or automatic upstream synchronization.
