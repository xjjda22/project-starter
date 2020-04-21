# project starter

## Features
- **Framework**: Express
- **Code**: ESLint, Prettier, Husky
- **Debuging**: Debug, VS Code configurations
- **Logging**: Winston
- **Testing**: Jest, SuperTest, AutoCannon
- **Continuous Integration**: GitHub Actions + Docker Compose
- **Other**: PM2, DotEnv

## Getting Started

```shell
# Install all dependencies
npm install

# Run on port 3000
npm start

Api Endpoint:
Method:HEAD

Case: Sample Api 
EndPoint:
Response:{
	
}

```

## Structure

```
.
├── config                  # App configuration files
│   ├── index.js        	# config
│   └── ...                 # Other configurations
├── db                      # Data access stuff
├── docs                    # Documentation
├── helpers                 # Helpers (formats, validation, etc)
├── services                # External services implementation  
│   ├── controllers         # Request managers
│   ├── middlewares         # Request middlewares
│   └── routes.js           # Define routes and middlewares here
├── scripts                 # Standalone scripts for dev uses
├── tests                   # Testing
├── .env                    # Environment variables
├── app.js                  # App starting point
├── Dockerfile              # Dockerfile
├── process.json            # pm2 init
├── package.json
└── README.md         
```