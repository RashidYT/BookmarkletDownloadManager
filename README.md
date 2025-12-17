# BookmarkletDownloadManager
this is bookmarklet to fetching media on the site you are on.

this is the supported element that are fetchable as of right now.

[Bookmarklet](javascript:(function()%7Basync%20function%20setupdm()%20%7B%0A%20%20%20%20%20%20%20%20try%20%7B%0A%20%20%20%20%20%20%20%20const%20response%20%3D%20await%20fetch(%22https%3A%2F%2Fraw.githubusercontent.com%2FRashidYT%2FBookmarkletDownloadManager%2F0ba764fa2958016d096c0c57cf5c6120c828f5af%2Fdownloadmanager%2Findex.html%22)%0A%0A%20%20%20%20%20%20%20%20const%20htmlString%20%3D%20await%20response.text()%3B%0A%0A%20%20%20%20%20%20%20%20var%20downloadmanager_div%20%3D%20document.createElement(%22div%22)%0A%20%20%20%20%20%20%20%20downloadmanager_div.id%20%3D%20%22downloadmanager_div%22%0A%20%20%20%20%20%20%20%20downloadmanager_div.innerHTML%20%3D%20htmlString%0A%20%20%20%20%20%20%20%20document.body.appendChild(downloadmanager_div)%0A%20%20%20%20%7D%20catch%20(error)%20%7B%0A%20%20%20%20%20%20%20%20console.error(%22Error%3A%20%22%20%2B%20error)%0A%20%20%20%20%7D%0A%20%20%20%20%7D%0A%0Asetupdm()%7D)()%3B)


| Element | Description                              |
|---------|------------------------------------------|
| img     | It would show pictures on the previewer. |
| video   | It would show a video on the previewer.  |
