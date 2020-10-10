# BugReportSPMLibraryWithCoreData

This is a Swift Package used for bug reporting the "unexpected character in prerequisites at position ..." SPM issue.

- If you add this package as a dependency (version **1.0.1**) in your app then it will break archiving with the "unexpected character in prerequisites at position ..." or it generate an empty archive (Generic Xcode Archive) for your app.

- The archiving issue will be fixed if you use the **1.0.0** version.
