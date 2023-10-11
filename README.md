```go
package overview

func aboutMe() map[string]string {
	return map[string]string{
		"Name":     "Khaiz Badaru Tammam",
		"LinkedIn": "linkedin.com/in/khaizbt",
	}
}

func getCurrentWorkplace() map[string]string {
	return map[string]string{
		"company":  "PT Privy Identitas Digital",
		"position": "Backend Engineer",
	}
}

func getDailyKnowledge() map[string]interface{} {
	return map[string]interface{}{
		"Programming Language": []string{
			"Golang",
			"PHP (Laravel)",
			"Javascript",
		},
		"Database": []string{
			"MySQL",
			"MongoDB",
			"ElasticSearch",
			"Redis"
		},
		"Other": []string{
			"Docker",
			"Pub/Sub",
			"Problem Solving",
			"Sistem Analyst",
		},
	}
}

func getFutureGoal() string {
	return "To Contribute on Open Source"
}

func getAvailableNow() string {
	return "I'm looking for Freelance Job"
}

```
