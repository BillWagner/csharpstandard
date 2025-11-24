I need you to apply a series of git patches to this repository in order. I'll provide URLs to the patch files. For each patch:

1. Download the patch file from the URL using curl
2. Apply it using `git apply` or `git am`
3. If there are merge conflicts (especially in ANTLR grammar productions in the standard folder, resolve them by:
   - Reading the conflicted files
   - Understanding both the incoming changes and the current state
   - Manually editing the files to incorporate both sets of changes correctly
   - For ANTLR grammar conflicts, ensure the grammar rules remain syntactically valid
4. Stage the resolved files with `git add`
5. Continue to the next patch

After applying all patches successfully, provide a summary of what was changed.

Here are the patch URLs in order:

1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1221.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1454.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1461.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1462.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1464.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1465.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1466.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1467.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1468.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1469.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1470.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1471.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1472.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1452.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1457.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1460.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1458.patch
1. https://patch-diff.githubusercontent.com/raw/dotnet/csharpstandard/pull/1459.patch