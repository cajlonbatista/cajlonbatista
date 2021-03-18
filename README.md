#### Sempre me esqueço então coloquei aqui
```
{
  "compilerOptions": {
    "module": "esnext",
    "target": "es2015",
    "jsx": "react-jsx",
    "strict": true,
    "skipLibCheck": true,
    "forceConsistentCasingInFileNames": true,
    "lib": [
      "dom",
      "dom.iterable",
      "esnext"
    ],
    "allowJs": true,
    "esModuleInterop": true,
    "allowSyntheticDefaultImports": true,
    "noFallthroughCasesInSwitch": true,
    "moduleResolution": "node",
    "resolveJsonModule": true,
    "isolatedModules": true,
    "noEmit": true
  },
  "include": [
    "src"
  ]
}
```
```
{
  "env": {
    "browser": true,
    "es2021": true,
    "node": true
  },
  "extends": ["plugin:react/recommended", "airbnb"],
  "parser": "@typescript-eslint/parser",
  "parserOptions": {
    "ecmaFeatures": {
      "jsx": true
    },
    "ecmaVersion": 12,
    "sourceType": "module"
  },
  "plugins": ["react", "@typescript-eslint"],
  "rules": {
    "import/no-anonymous-default-export": "off",
    "no-console": "off",
    "react/react-in-jsx-scope": "off",
    "import/no-unresolved": "off",
    "space-before-function-paren": "off",
    "import/prefer-default-export": "off",
    "react/prop-types": "off",
    "react-in-jsx-scope": "off",
    "import/extensions": [
        "error",
        {
          "ts": "never",
          "tsx": "never"
        }
     ],  
    "react/jsx-filename-extension": [1, { "extensions": [".tsx"] }]
  }
}
```
