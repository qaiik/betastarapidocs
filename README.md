# betastarapidocs
The documentation for the betastar api. | warning - this is very in development, and is not done |

Getting a user:<br> GET https://betastar.org/api/user/?name=username <br>//{ "atoms": 0, "element": "", "role": "Common", "color": "#FFFFFF", "linked": "none" }

Setting your avatar: POST https://betastar.org/api/setavatar/ json={element: "yourelement"} headers={cookie: "yourbetastarcookie"}
