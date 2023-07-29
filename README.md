# Github resource community data

games:

``` ts
interface game
{
    id:string
    name:string
    dataRepo:string // style: user/repo
    steamAppName:string?
    relativeRootInstallPath:string?
    autoMkRelativeRootInstallPath:boolean?
    icon:string?
}
```