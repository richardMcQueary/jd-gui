```


git clone https://github.com/richardMcQueary/jd-gui.git C:\Users\rmcquear\jd-gui2


# git clone https://github.com/java-decompiler/jd-gui.git
SET swing.defaultlaf=C:\Users\rmcquear\lafbacking.xml
cd jd-gui
.\gradlew build

# OUTPUT:
# .\build\libs\*.jar

jd-gui/services/src/main/resources/rsyntaxtextarea/themes/eclipse.xml 
<baseFont size="18"/>

jd-gui.cfg
/configuration/gui/lookAndFeel


jd-gui/app/src/main/java/org/jd/gui/service/configuration/ConfigurationXmlPersisterProvider.java

  SynthLookAndFeel laf = new SynthLookAndFeel();
  laf.load(new URL("file:///C:/java/synth/laf/laf.xml"));
  UIManager.setLookAndFeel(laf);



SET swing.defaultlaf=C:\Users\rmcquear\laf.xml

<synth>
  <style id="basicStyle">
    <font name="Verdana" size="18"/>
    <state>
      <color value="BLACK" type="BACKGROUND"/>
      <color value="WHITE" type="FOREGROUND"/>
    </state>
  </style>
  <bind style="basicStyle" type="region" key=".*"/>
</synth>





-Djd-gui.cfg=path/to.jd-gui.cfg



UIManager.put("Label.font", new FontUIResource(new Font("Dialog", Font.PLAIN, 18)));
UIManager.put("Button.font", new FontUIResource(new Font("Dialog", Font.BOLD, 18)));
UIManager.put("TextField.font", new FontUIResource(new Font("Dialog", Font.PLAIN, 18)));



```
