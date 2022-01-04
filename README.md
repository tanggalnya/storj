# Storj

## How to start
1. Install uplink [here](https://docs.storj.io/dcs/downloads/download-uplink-cli)
1. Create new access [here](https://ap1.storj.io/access-grants)
1. Import access
    ```
    uplink import project-name access-grant-xx.key
    ```
    Replace project-name and access grant

## Command line
- Upload
    ```
    uplink cp ~/Desktop/cheesecake.jpg sj://cakes
    ```
- Share
    ```
    uplink --access project-name share --url sj://bucket/filename --not-after=none
    ```
- List
    ```
    uplink ls sj://website
    ```
- Download
    ```
    uplink cp sj://bucket/filename ./filename
    ```
- Delete
    ```
    uplink rm sj:/bucket/filename
    ```

## Related docs
- [presigned url](https://docs.storj.io/dcs/api-reference/s3-compatible-gateway/using-presigned-urls)
- [embed file](https://forum.storj.io/t/what-happend-to-the-view-option-for-a-linkshare/12388/16)
