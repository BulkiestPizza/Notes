04-02-2022 at 22:20

---
# Navigation
---


# Navigator.Push
		onPressed:() {
			Navigator.push(
				context,
				MaterialPageRoute(builder: (context) => const ##Widget to go to")
			)
		}

Push() method adds a Route to a stack of routes managed by Navigator. The Route can be created by you or you can use MaterialPageRoute, which adds a transition (I have no idea for the point of context, though https://stackoverflow.com/questions/59514627/what-is-each-context-word-referring-to-in-navigator-push might help)

# Navigator.pop()
			onPressed:() {
				Navigator.pop(context)
			}
The context refers, i assume, to the cached route that the user used to get th


## References 
https://docs.flutter.dev/cookbook/navigation/navigation-basics
https://stackoverflow.com/questions/59514627/what-is-each-context-word-referring-to-in-navigator-push
