# pcf
pcf templates and other assets to assits #PowerPlatformProDevelopers

Reference the cds.css file in the ControlManifest.xml and add the input class .cds-input to your input componen, as displayed in the sample below
<!-- ControlManifest.xml  -->
<resources>
  <code path="index.ts" order="1"/>
  <css path="css/cds.css" order="1" />
</resources>

//index.ts
this.inputElement.setAttribute("class", "cds-input");

