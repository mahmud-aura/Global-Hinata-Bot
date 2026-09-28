# **Global Ban Storage Directory**

GoatBot stores global bans in a dedicated directory called Data-Gban-GoatBot-Project at the root level of the project. This directory contains ban files for each user who has been globally banned.

The forbidden file is an object containing multiple entries, each of which represents a banned user. Each entry has a unique identifier as its key and contains the reason for the ban, the proof (e.g. a screenshot), and the date of the ban. The proof is stored as an array of URLs pointing to the location of the proof files.

* `id`: the ID of the banned user
* `reason`: the reason for the ban
* `proof`: an array of URLs to proof of the ban
* `date`: the timestamp of the ban in ISO 8601 format
* **Here's an example ban file for a user with ID 123456789:**

```json
{
	"123456789": {
		"reason": "Spamming the chat",
		"proof": [
			"https://example.com/proof1.jpg",
			"https://example.com/proof2.mp4"
		],
		"date": "2023-04-02T12:12:12+0000"
	}
}
```
---

Any questions or complaints please contact with the information below:
<table>
<tr>
<td align="center"><a href="https://www.facebook.com/mahmudexe"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"></a>
</td>
<td align="center"><a href="https://instagram.com/mahmud.x07"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
</td>
</tr>

<tr>
<td align="center"><a href="https://www.youtube.com/@mahmud-aura"><img src="https://img.shields.io/badge/Youtube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"></a>
</td>
<td align="center"><a href="https://wa.me/8801836298139"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"></a>
</td>
</tr>

<tr>
<td align="center"><a href="https://mahmud-aura.is-a.dev/"><img src="https://img.shields.io/badge/Portfolio-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
</td>
<td align="center"><a href="mailto:mahmudx077@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</td>
</tr>

<tr>
<td align="center" colspan=2><a href="https://github.com/mahmud-aura"><img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=github&logoColor=white"></a>
</td>
</tr>
</table>
