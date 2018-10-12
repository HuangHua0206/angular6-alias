# angular6-alias
 * angular将webpack内置于nodemodules中，开发者需要webpack中alias的功能实现 
 #### 代码 
 #### 在住目录找到 tsconfig.json 和 src/tsconfig.app.json 下找到compilerOptions修改paths即可实现webpack的alias功能即可 
 `"paths": { 
      "@admin/*": ["admin/*"], 
      "@api/*": ["api/*"], 
      "@app/*": ["app/*"], 
      "@components/*": ["components/*"], 
      "@environments/*": ["environments/*"], 
      "@less/*": ["less/*"], 
      "@pages/*": ["pages/*"], 
      "@router/*": ["router/*"], 
      "@utils/*": ["utils/*"], 
      }`
