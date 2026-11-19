# Finalpool

- Source: Notion **Task Tracker** database (`41d13c0b-3bc1-81b8-be9f-e0dd542a4d63`)
- Base path: `tasks/finalpool`
- Included implemented tasks: **54**
- Excluded implementing tasks: **33**
- Total Notion tasks reconciled: **87**
- Inclusion rule: Notion `Task Status` = `implemented`
- Marker pattern: `tasks/finalpool/{task-name}/.gitkeep`
- Full task records: [`MANIFEST.csv`](./MANIFEST.csv)
- Summary metadata: [`manifest.json`](./manifest.json)

Each included task is represented by a `.gitkeep` marker at the required relative path. The task-directory names match the Notion **Task Name** values; owner and Notion page-ID mappings are recorded in `MANIFEST.csv`.

## Verification

- Expected marker files: **54**
- Marker files successfully read through the GitHub Contents API: **54/54**
- Negative spot-check: `tasks/finalpool/lead-tracker` was absent; this task remains `implementing` and has no generated marker.
- Sorted implemented-task-name checksum (SHA-256 prefix): `9c6feabfed534298`
- Markers generated for excluded (`implementing`) tasks by this audit job: **0**

## Implemented tasks by owner

| Owner | Implemented tasks |
| --- | ---: |
| fan-dev | 2 |
| gyy | 4 |
| haoze | 2 |
| jl_dev | 3 |
| junteng_dev | 7 |
| junxian_dev | 2 |
| lueyang-dev | 6 |
| lv | 5 |
| ruige | 4 |
| wenshuo-dev | 2 |
| xiaochen_dev | 5 |
| yuxuan-dev | 4 |
| yuzhen-dev | 6 |
| zhaochen | 2 |
