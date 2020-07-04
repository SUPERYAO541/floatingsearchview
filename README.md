# floatingsearchview
Modified from [arimorty-floatingsearchview](https://github.com/arimorty/floatingsearchview).

## Modify
* Migrated to AndroidX
* Upgrade support libs to the latest
* Disable group_divider from ListMenuItemView (Overflow menu)
	* before  
		![Alt text](https://i.imgur.com/PkWmgyT.png "before")
	* after  
		![Alt text](https://i.imgur.com/8oy45Cp.png "after")
  
## Usage
1. Put [aar-release](https://github.com/SUPERYAO541/floatingsearchview/tree/master/aar-release)'s files to yourProject/app/libs
2. Add below code to your Gradle of app-level:
```
dependencies {  
	implementation fileTree(dir: 'libs', include: ['*.jar', '*.aar'])  
	...  
}
```
3. About how to use it, please read [arimorty-floatingsearchview](https://github.com/arimorty/floatingsearchview)'s doc.
