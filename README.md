# LINE Notify API Template for Python 3

> [!IMPORTANT]
> **Archived / no longer actively maintained.**
>
> LINE Notify was discontinued on **March 31, 2025**. From April 1, 2025, the LINE Notify APIs, including `notify-api.line.me`, are no longer available. This repository is preserved as a historical Python example and is not expected to work against the retired service.

## Historical purpose

This repository demonstrated a minimal Python 3 request to the LINE Notify API.

The original example is retained in `LINENotifyAPI_Template.py` for reference. Do not create or embed credentials for the retired LINE Notify service.

## Final dependency snapshot

The example imports `requests`. For reproducibility, the final archived dependency snapshot is recorded in `requirements.txt`.

- Python: **3.10+** (required by the recorded Requests release)
- Requests: **2.34.2**
- Live API verification: **not applicable**, because LINE Notify has been discontinued

Install the historical dependency snapshot with:

```console
python -m pip install -r requirements.txt
```

## Successor

For current LINE integrations that send messages, use the **LINE Messaging API** instead:

- https://developers.line.biz/en/docs/messaging-api/
- Service termination notice: https://developers.line.biz/en/news/2025/04/01/line-notify/

## Repository status

No further feature development, dependency automation, CodeQL schedules, or bot-driven maintenance is planned for this repository. The repository is intentionally kept public and read-only as historical reference after archival.
