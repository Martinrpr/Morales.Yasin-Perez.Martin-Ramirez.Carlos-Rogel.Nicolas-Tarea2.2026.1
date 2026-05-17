JAVAFX_PATH = C:/Users/Carlos/javafx21/lib
MODS        = javafx.controls,javafx.fxml
JAVAC       = "C:/Program Files/Java/jdk-26/bin/javac.exe"
JAVA        = "C:/Program Files/Java/jdk-26/bin/java.exe"

all:
	$(JAVAC) --module-path "$(JAVAFX_PATH)" --add-modules $(MODS) -d . src/*.java

run: all
	$(JAVA) --module-path "$(JAVAFX_PATH)" --add-modules $(MODS) Stage3

clean:
	rm -f *.class
