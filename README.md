UIImage-Save
============

A simple category on UIImage to easily save to photos album
-----------------------------------------------------------

Usage:

```
        UIImage *sampleImage = [UIImage imageNamed:@"sample.png"];
        [sampleImage saveToPhotosAlbumOnSuccess:^{
                                              //Do something on success
                                             }
                                             onError:^(NSError *error){
                                              //Do something on error
                                             }
         ];
```


*Tested on **iOS7** using **ARC**.*

