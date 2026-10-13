# verify-record

- commit: `1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e`
- stage: prereg
- ok: yes
- rows: 15 = mismatch 0 / skipped 12 / ok 3

## mismatch（problems）

_なし_

## skipped（比べていない: 人間と judge が読む）

| status | path | reason | links |
| --- | --- | --- | --- |
| skipped | `hypotheses[h1]/statement` | no check | [record.json#L5](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json#L5) |
| skipped | `hypotheses[h1]/assumptions[0]` | no check | [record.json#L7](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json#L7) |
| skipped | `hypotheses[h1]/claims[c1]/statement` | no check | [record.json#L12](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json#L12) |
| skipped | `hypotheses[h1]/claims[c1]/rationale` | no check | [record.json#L13](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json#L13) |
| skipped | `hypotheses[h1]/claims[c1]/verifier` | no check | [record.json#L14](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json#L14) |
| skipped | `hypotheses[h1]/claims[c1]/designs[d1]/summary` | no check | [record.json#L20](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json#L20) |
| skipped | `hypotheses[h1]/claims[c1]/designs[d1]/runs[proposed]/description` | no check | [record.json#L24](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json#L24) |
| skipped | `hypotheses[h1]/claims[c1]/designs[d1]/runs[proposed]/params/mode` | no check | [record.json#L26](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json#L26) |
| skipped | `hypotheses[h1]/claims[c1]/designs[d1]/runs[baseline]/description` | no check | [record.json#L31](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json#L31) |
| skipped | `hypotheses[h1]/claims[c1]/designs[d1]/runs[baseline]/params/mode` | no check | [record.json#L33](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json#L33) |
| skipped | `hypotheses[h1]/claims[c1]/prediction` | no check | [record.json#L46](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json#L46) |
| skipped | `hypotheses[h1]/notes[0]` | no check | [record.json#L54](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json#L54) |

<details><summary>ok（3 行）</summary>

| status | path | reason | links |
| --- | --- | --- | --- |
| ok | `hypotheses[h1]/claims[c1]/criterion` | subject 'proposed' among this claim's runs | [record.json#L39](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json#L39) [.research/record.json](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json) |
| ok | `hypotheses[h1]/claims[c1]/criterion` | reference 'baseline' among the record's seyval runs | [record.json#L39](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json#L39) [.research/record.json](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json) |
| ok | `.research/record.json` | every committed version contains its parent and names only passages it held | [.research/record.json](https://github.com/auto-res2/verify-report-check-2/blob/1c7a5e616ad7a9d49e3b57a6acc80b505aa38f7e/.research/record.json) |

</details>
