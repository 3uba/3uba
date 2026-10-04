# `whoami`

Some dev from the internet. Writes tools nobody asked for, then uses them anyway.

Bio generators are for people with a personality to summarize, so instead here's
a flag. Decode it and you've technically done more research on me than most
recruiters.

```
63444177575874314d563878656c387a5344673066513d3d
```

<details>
<summary>can't crack it? 🫠 (it's not even hard, come on)</summary>

Three layers. Onion-style. Try not to cry.

```bash
echo '63444177575874314d563878656c387a5344673066513d3d' \
  | xxd -r -p \                    # layer 1: it's hex. shocking.
  | base64 -d \                    # layer 2: base64, obviously
  | tr 'A-Za-z' 'N-ZA-Mn-za-m'     # layer 3: ROT13, the final boss
```

If that was too much effort, the answer is: you should've just said hi.

</details>

---

<sub>warning: repos may contain traces of "it works on my machine" and 3am commits</sub>
