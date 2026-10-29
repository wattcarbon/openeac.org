# openeac.org

The public site of the OpenEAC Alliance, served at https://www.openeac.org by
GitHub Pages. It is the front door: what the Alliance is, how a methodology is
approved, the meetings, the governance, and how to join.

Two other places hold the rest, and this site links to both:

- **Methodologies**: https://methods.openeac.org, built from
  [wattcarbon/open-eac-alliance](https://github.com/wattcarbon/open-eac-alliance).
  Certificates cite methodology URLs on that host, so it stays where it is.
- **Newsletter and post archive**: https://openeac.substack.com.

## Common edits

| To change | Edit |
| --- | --- |
| The next meeting | `_data/next_meeting.yml` |
| Add a past meeting | `_data/meetings.yml`, newest first |
| Page copy | `index.html`, `methodologies.md`, `meetings.html`, `governance.md`, `join.html` |

`_redirects/` forwards each address the site had on Substack, such as
`/p/<slug>`, to the same post on openeac.substack.com. A post published after
the move already has a Substack address and needs no stub.

## Preview

```sh
docker compose up      # then open http://localhost:4000
```
