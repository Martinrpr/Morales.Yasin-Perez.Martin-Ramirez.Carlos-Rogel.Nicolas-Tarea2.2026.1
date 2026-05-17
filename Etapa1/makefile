.PHONY: all run clean

JAVAFX_PATH = C:/Users/MARTIN PEREZ ROJAS/Desktop/openjfx-26.0.1_windows-x64_bin-sdk/javafx-sdk-26.0.1/lib

MODS = javafx.controls,javafx.fxml

JAVAC = "C:/Program Files/Java/jdk-26/bin/javac.exe"
JAVA = "C:/Program Files/Java/jdk-26/bin/java.exe"

all:
	$(JAVAC) --module-path "$(JAVAFX_PATH)" --add-modules $(MODS) -d . src/*.java

run: all
	$(JAVA) --module-path "$(JAVAFX_PATH)" --add-modules $(MODS) Stage1

clean:
	del /Q *.class
