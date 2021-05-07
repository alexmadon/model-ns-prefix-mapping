# Alfresco Model Namespace-Prefix Mapping

This project includes a Repository WebScript to get a map of (namespace,prefix) for every deployed content model.

Once installed, as a regular Repository addon, following URL is available:

http://127.0.0.1:8080/alfresco/s/model/ns-prefix-map

Sample response:

```
{
  "prefixUriMap": {
    "http://www.alfresco.org/model/custommodelmanagement/1.0": "cmm",
    "http://www.alfresco.org/model/publishing/slideshare/1.0": "slideshare",
    "http://www.alfresco.org/model/publishing/linkedin/1.0": "linkedin",
    "http://www.alfresco.org/model/datalist/1.0": "dl",
    "http://www.alfresco.org/model/publishing/facebook/1.0": "facebook",
    "http://www.alfresco.org/model/emailserver/1.0": "emailserver",
    "http://www.alfresco.org/model/distributionpolicies/1.0/model": "dp",
    "http://www.alfresco.org/model/publishing/youtube/1.0": "youtube",
    "http://www.alfresco.org/model/action/1.0": "act",
    "http://www.alfresco.org/model/system/1.0": "sys",
    "http://www.alfresco.org/model/cmis/1.0/cs01": "cmis",
    "http://www.alfresco.org/model/bpm/1.0": "bpm",
    "http://www.alfresco.org/model/publishing/twitter/1.0": "twitter",
    "http://www.alfresco.org/model/dictionary/1.0": "d",
    "http://www.alfresco.org/model/linksmodel/1.0": "lnk",
    "http://www.alfresco.org/model/workflow/invite/moderated/1.0": "imwf",
    "http://www.alfresco.org/model/googledocs/2.0": "gd2",
    "http://www.alfresco.org/model/workflow/invite/nominated/1.0": "inwf",
    "http://www.alfresco.org/model/content/1.0": "cm",
    "http://www.alfresco.org/model/forum/1.0": "fm",
    "http://www.alfresco.org/model/remotecredentials/1.0": "rc",
    "http://www.alfresco.org/model/calendar": "ia",
    "http://www.alfresco.org/model/versionstore/2.0": "ver2",
    "http://www.alfresco.org/model/content/smartfolder/1.0": "smf",
    "http://www.alfresco.org/model/cmis/custom": "cmiscustom",
    "http://www.alfresco.org/model/site/1.0": "st",
    "http://www.alfresco.org/model/solrfacet/1.0": "srft",
    "http://www.alfresco.org/model/application/1.0": "app",
    "http://www.alfresco.org/model/imap/1.0": "imap",
    "http://www.alfresco.org/model/aos/1.0": "aos",
    "http://www.alfresco.org/model/transfer/1.0": "trx",
    "http://www.alfresco.org/model/versionstore/1.0": "ver",
    "http://www.alfresco.org/model/surf/1.0": "surf",
    "custom.model": "custom",
    "http://www.alfresco.org/model/publishing/1.0": "pub",
    "http://www.alfresco.org/model/qshare/1.0": "qshare",
    "http://www.alfresco.org/model/workflow/1.0": "wf",
    "http://www.alfresco.org/model/download/1.0": "download",
    "http://www.alfresco.org/model/user/1.0": "usr",
    "http://www.alfresco.org/model/blogintegration/1.0": "blg",
    "http://www.alfresco.org/model/rule/1.0": "rule",
    "http://www.alfresco.org/model/publishing/flickr/1.0": "flickr",
    "http://www.alfresco.org/model/workflow/resetpassword/1.0": "resetpasswordwf",
    "": ""
  }
}
```

>> This project has been tested with ACS 7.0.0