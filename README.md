# BugReportSPMLibraryWithCoreData

This is a Swift Package used for bug reporting the "error: error reading dependency file '...': unexpected character in prerequisites at position ..." SPM issue.

If you add the **1.0.1** version of this package as a dependency in your app then it will break the archiving of the app with the "unexpected character in prerequisites at position ..." or it generate an empty archive (Generic Xcode Archive) for your app, but if you use the **1.0.0** version of this package everything works just fine.

rdar://FB8790797
