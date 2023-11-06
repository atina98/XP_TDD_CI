# Continous Integration (CI)
by Atina Maurer

## Was ist CI?
CI ist eine agile Methode in der Softwareentwicklung, bei der Entwickler:innen regelmäßig ihren Code in ein gemeinsames Repository integrieren. Das Hauptziel von CI besteht darin, sicherzustellen, dass Codeänderungen kontinuierlich und automatisch getestet und in das Hauptprojekt integriert werden, um die Qualität der Software und die Zusammenarbeit im Entwickler:innenteam zu verbessern.

## Ziele
- **Regelmäßige Integration:** Entwickler:innen führen kontinuierlich kleine Codeänderungen in das gemeinsame Repository ein, anstatt größere, isolierte Änderungen vorzunehmen. Dadurch werden Konflikte und Probleme frühzeitig erkannt und behoben.
- **Automatisierung:** CI-Systeme automatisieren den Build- und Testprozess. Dies bedeutet, dass bei jeder Code-Änderung automatisch eine neue Version der Software erstellt und Tests ausgeführt werden. Dies spart Zeit und Entwickler:innen können sich voll und ganz aufs Programmieren konzentireren.
- **Auto-Tests:** Verschiedene Arten von Tests werden automatisiert ausgeführt, wie z. B. Einheitstests, Integrationstests und Akzeptanztests. Dies hilft, Fehler frühzeitig zu erkennen und die Qualität der Software sicherzustellen.
- **Frühzeitige Fehlererkennung:** Fehler und Probleme im Code sollen, aufgrund von Auto-Tests, frühzeitig identifizierbar sein, bevor sie sich zu schwerwiegenden und kostspieligen Fehlern in der Produktion entwickeln.
- **Einfachere Zusammenarbeit im Team:** Alle Teammitglieder arbeiten in einem gemeinsamen Repository und integrieren kontinuierlich ihre Codeänderungen. Dies fördert die Zusammenarbeit und sorgt dafür, dass alle auf dem gleichen Stand sind.
- **Bessere Verwaltung und Transparenz:** CI-Systeme bieten Transparenz über den Status des Projekts und helfen bei der Verwaltung von Versionskontrollen, Änderungsverfolgung und Berichterstellung.
- **Schnellere Markteinführungen:** Die effiziente Verwaltung von Codeänderungen und die schnelle Fehlerbehebung ermöglichen es, neue Funktionen und Verbesserungen schneller auf den Markt zu bringen.

## CI in 6 easy steps:
1. Write and push yout code
2. Build automatically
3. Test automatically
4. Get your feedback
5. Integrate into the main repository
6. **Continuous Integration**

## CI/CD Pipeline 
Eine CI/CD-Pipeline ist ein automatisierter Prozess in der Softwareentwicklung, der Continuous Integration (CI) und Continuous Deployment (CD) kombiniert, um Softwareänderungen effizient und zuverlässig bereitzustellen.

![CI/CD Pipeline](https://www.parasoft.com/wp-content/uploads/2021/04/CICD_CICD.png.webp)

- **CI:** In dieser Phase werden Codeänderungen automatisch in ein gemeinsames Repository integriert, nachdem sie auf Build-Fähigkeit und Fehler getestet wurden. Die CI-Phase gewährleistet die kontinuierliche Integration von Code und die frühzeitige Fehlererkennung.
- **CD:** Nach erfolgreicher CI wird der Code automatisch in die Produktionsumgebung übertragen, wodurch Softwareänderungen schnell und automatisch an die Benutzer ausgeliefert werden. Nach Feedback und Evaluation, kann es dann wieder in die CI Phase gehen, wenn Erweiterungen und/oder Änderungen gewünscht sind.

## GitHub Actions
GitHub Actions ermöglicht die Automatisierung von Software-Entwicklungs-Workflows und kann CI/CD-Pipelines erstellen und steuern.

- **Einrichtung von Workflows:** Benutzerdefinierte Workflows können erstellt werden, die automatische Aktionen ausführen, wenn bestimmte Ereignisse in einem GitHub-Repository auftreten. Diese Workflows werden in einer Datei im Repository (normalerweise .github/workflows) definiert.
- **Automatisierte Aufgaben:** Innerhalb eines Workflows können automatisierte Aufgaben und dessen Auslöser (zB push/pull requests) definiert werden. Dies können Schritte wie das Erstellen des Build-Prozesses, das Ausführen von Tests, das Erstellen von Artefakten oder das Bereitstellen in der Produktionsumgebung sein. Diese Aufgaben werden in einem YAML-Dateiformat innerhalb des Workflow-Files beschrieben.
- **Integration von CI:** GitHub Actions erleichtert die Integration von CI in den Entwicklungsprozess. Ein typischer CI-Workflow umfasst beispielsweise das Klonen des Repositorys, das Installieren von Abhängigkeiten, das Erstellen der Anwendung, das Ausführen von Tests und das Generieren von Berichten. Die Ergebnisse dieser Schritte werden im Workflow überprüft.
- **Feedback und Benachrichtigungen:** Es wird Feedback in Form von Workflow-Status und detaillierten Berichten über den Erfolg oder das Scheitern der automatisierten Aufgaben gesendet. Man wird benachrichtigt, wenn ein Workflow fehlschlägt, was hilft, Probleme zu erkennen und zu beheben.

## Quellen
[redhat.com](https://www.redhat.com/topics/devops/what-is-ci-cd)\
[jetbrains.com](https://www.jetbrains.com/teamcity/ci-cd-guide/continuous-integration/)\
[atlassian.com](https://www.atlassian.com/continuous-delivery/continuous-integration)\
[wikipedia.org](https://en.wikipedia.org/w/index.php?title=Continuous_integration&oldid=1169653496)\
[github.com](https://github.com/features/actions)




