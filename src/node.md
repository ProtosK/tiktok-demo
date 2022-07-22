1. cài thư viện: npm i customize-cra react-app-rewired -D rồi tạo file config-overrides.js để sử dụng.
2. cấu hình lại package đổi tên trong script từ "react-scripts start" thành "react-app-rewired start".
3. npm install --save-dev babel-plugin-module-resolver, tạo file .babelrc và jsconfig.js rồi cấu hình path
4. cấu hình babelrc cho webpack (trong file config-overrides.js) hiểu
