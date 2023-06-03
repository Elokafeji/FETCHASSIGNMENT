# FETCHASSIGNMENT
FETCH CODE CHALLENGE FIX code main.go


package main

import (
	"github.com/gin-gonic/gin"
)

func main() {
	router := gin.Default()

	// Define your API routes here

	router.Run(":8080")
}
