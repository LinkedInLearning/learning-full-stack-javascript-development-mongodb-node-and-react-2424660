# Learning Full-Stack JavaScript Development: MongoDB, Node, and React
This is the repository for the LinkedIn Learning course Learning Full-Stack JavaScript Development: MongoDB, Node, and React. The full course is available from [LinkedIn Learning][lil-course-url].

![Learning Full-Stack JavaScript Development: MongoDB, Node, and React][lil-thumbnail-url] 

Learn by doing! Learn full-stack JavaScript development by building a web application with MongoDB, Node.js, and React.js.

Learn how to use Node as a web server and an API server, how to consume data and build user interfaces with React, and how to read and write data with a MongoDB database. React allows you to build full-featured, data-driven applications faster and more efficiently than what is possible with JavaScript alone.

Samer Buna introduces modern JavaScript programming concepts, with an emphasis on functional methods and open-source tools. The lessons are almost completely hands-on, with live coding demonstrations that bring the concepts home.



Video Course (recorded August 2022): **[samer.dev/mnr](https://samer.dev/mnr)**

For an up-to-date development environment configuration guide: **[samer.dev/reactful-ts](https://samer.dev/reactful-ts)**

For general help: **[jscomplete.com/help](https://jscomplete.com/help)**

### Reference Text

#### package.json scripts

```
  "scripts": {
    "dev:server": "tsnd src/server/server.ts",
    "dev:bundler": "webpack -w --mode=development"
  },
```

#### package.json dependencies

```
  "dependencies": {
    "axios": "^0.27.2",
    "cors": "^2.8.5",
    "ejs": "^3.1.8",
    "express": "^4.18.1",
    "mongodb": "^4.8.1",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "ts-loader": "^9.3.1",
    "typescript": "^4.7.4",
    "webpack": "^5.74.0",
    "webpack-cli": "^4.10.0"
  },
  "devDependencies": {
    "@typescript-eslint/parser": "^5.33.0",
    "eslint": "^8.22.0",
    "eslint-plugin-react": "^7.30.1",
    "eslint-plugin-react-hooks": "^4.6.0",
    "prettier": "^2.7.1",
    "ts-node-dev": "^2.0.0"
  }
```

#### Mock Data

```json
{
  "contests": [
    {
      "id": "cognitive-building-bricks",
      "categoryName": "Business/Company",
      "contestName": "Cognitive Building Bricks"
    },
    {
      "id": "educating-people-about-sustainable-food-production",
      "categoryName": "Magazine/Newsletter",
      "contestName": "Educating people about sustainable food production"
    },
    {
      "id": "big-data-analytics-for-cash-circulation",
      "categoryName": "Software Component",
      "contestName": "Big Data Analytics for Cash Circulation"
    },
    {
      "id": "free-programming-books",
      "categoryName": "Website",
      "contestName": "Free programming books"
    }
  ]
}
```

### Instructor

Samer Buna 
                            


                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/samer-buna).

[lil-course-url]: https://www.linkedin.com/learning/learning-full-stack-javascript-development-mongodb-node-and-react-15581237?dApp=59033956
[lil-thumbnail-url]: https://media.licdn.com/dms/image/C560DAQGx_lsYcLsXOA/learning-public-crop_675_1200/0/1671474208254?e=2147483647&v=beta&t=VWBgbqX4HosB4nvBrs6_xcEz7YpTKlRNMdUnpTDwK7o
