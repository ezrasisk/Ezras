import { defineConfig } from "@junobuild/config";

export default defineConfig({
  satellite: {
    id: "ckahl-nyaaa-aaaal-ar5gq-cai",
    source: "./",
    storage: {
      headers: [
        {
          source: "/",
          headers: [["Cache-Control", "public,max-age=0,must-revalidate"]]
        },
        {
          source: "assets/fonts/*",
          headers: [["Cache-Control", "max-age=31536000"]]
        },
        {
          source: "**/*.jpg",
          headers: [
            ["Cache-Control", "max-age=31536000"],
            ["Access-Control-Allow-Origin", "*"]
          ]
        }
      ]
    }
  }
});
