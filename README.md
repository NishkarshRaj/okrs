# 🧭 OKRs

I use **Objectives and Key Results** both for my personal and professional life ([OKRs on Wikipedia](https://en.wikipedia.org/wiki/OKR)). This repository is the source of truth of my progress for my personal goals. I update these numbers weekly.

**API**: https://anandchowdhary.github.io/okrs/api.json

<!-- start autogenerated OKR summary -->

## 📈 Current OKRs – Q1 2022

<div>
  <table>
    <thead>
      <tr>
        <th>OKR</th>
        <th>Success</th>
        <th colspan="2">Progress</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>Daily Goals</strong></td>
        <td><strong>0%</strong></td>
        <td>⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜</td>
        <td><strong>0%</strong></td>
      </tr>
      <tr>
        <td>↳ 10k steps</td>
        <td>0%</td>
        <td>⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜</td>
        <td>0%</td>
      </tr>
    <tr>
        <td>↳ Publicly Learn and Share Code</td>
        <td>0%</td>
        <td>⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜</td>
        <td>0%</td>
      </tr>
    <tr>
        <td>↳ Start my day at [redacted]</td>
        <td>0%</td>
        <td>⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜</td>
        <td>0%</td>
      </tr>
    <tr>
        <td><strong>Weekly Goals</strong></td>
        <td><strong>0%</strong></td>
        <td>⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜</td>
        <td><strong>0%</strong></td>
      </tr>
      <tr>
        <td>↳ Publish a Blog Post</td>
        <td>0%</td>
        <td>⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜</td>
        <td>0%</td>
      </tr>
    <tr>
        <td>↳ Mobile screen time averages less than two hours a day</td>
        <td>0%</td>
        <td>⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜</td>
        <td>0%</td>
      </tr>
    <tr>
        <td>↳ Knowledge Share with the Community - Twitter Spaces, etc.</td>
        <td>0%</td>
        <td>⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜</td>
        <td>0%</td>
      </tr>
    <tr>
        <td><strong>Quarterly Goals</strong></td>
        <td><strong>0%</strong></td>
        <td>⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜</td>
        <td><strong>0%</strong></td>
      </tr>
      <tr>
        <td>↳ Read Books - [redacted]</td>
        <td>0%</td>
        <td>⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜</td>
        <td>0%</td>
      </tr>
    <tr>
        <td>↳ Certified in Cloud Native Tech</td>
        <td>0%</td>
        <td>⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜</td>
        <td>0%</td>
      </tr>
    <tr>
        <td>↳ Setup my Blog Post</td>
        <td>0%</td>
        <td>⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜</td>
        <td>0%</td>
      </tr>
    </tbody>
  </table>
</div>

<!-- end autogenerated OKR summary -->

## ℹ️ About this repository

If you want your own OKRs tracker, you can [fork this repository](https://github.com/AnandChowdhary/okrs/fork) and set up the repository with the following file structure:

```
├── README.md
├── .github
│   └── workflows
│       └── node.yml
└── okrs
    ├── 2019
    │   ├── 3.md
    │   └── 4.md
    └── 2020
        └── 1.md
```

Using GitHub Actions, `api.json` and `README.md` will be auto-generated. When creating new OKRs for a quarter, follow the [JSON schema](https://anandchowdhary.github.io/okrs/schema.json) by duplicating one of the files in the [`./okrs`](./okrs) directory:

```json
{
  "$schema": "https://anandchowdhary.github.io/okrs/schema.json",
  "year": 2021,
  "quarter": 4,
  "objectives": [
    {
      "name": "Objective 1",
      "key_results": [
        {
          "name": "Key result 1",
          "target_result": 10,
          "current_result": 1
        }
      ]
    }
  ]
}
```

You can use the git commit history as a way to track progress of an OKR, for example looking at the history of my Q4 2021 OKRs: https://github.com/AnandChowdhary/okrs/commits/main/okrs/2021/4.json. A more sophisticated system can be set up that tracks changes to one line using `git log` like so:

```bash
git log -L17,+1:'okrs/2021/4.json'
```

## 📄 License

- Code in the `scripts` directory: [MIT](./LICENSE) © [Anand Chowdhary](https://anandchowdhary.com)
- Content in the `okrs` directory: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) © [Anand Chowdhary](https://anandchowdhary.com)
- "GitHub" is a trademark of GitHub, Inc.
