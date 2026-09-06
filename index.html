const express = require("express");
const cors = require("cors");

const app = express();

app.use(cors({ optionsSuccessStatus: 200 }));

app.use(express.static("public"));

app.get("/", function (req, res) {
  res.sendFile(__dirname + "/views/index.html");
});

app.get("/api/:date?", function (req, res) {
  let date;

  // If no date was provided, use the current date and time
  if (!req.params.date) {
    date = new Date();
  } else {
    // Try to convert the provided date into a Date object
    date = new Date(req.params.date);

    // Check if the date is invalid
    if (isNaN(date.getTime())) {
      return res.json({
        error: "Invalid Date"
      });
    }
  }

  res.json({
    unix: date.getTime(),
    utc: date.toUTCString()
  });
});

const listener = app.listen(process.env.PORT || 3000, function () {
  console.log("Your app is listening on port " + listener.address().port);
});