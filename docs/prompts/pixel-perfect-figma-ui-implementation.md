Implement this UI design from Figma with perfect pixel accuracy, production ready code, better performance, focusing exclusively on the app content and ignoring any device frame elements (status bar, home indicator, etc.).

Key requirements:

1. **EXACT VISUAL MATCHING**:
   - Match all colors precisely using hex codes from the design
   - Implement correct spacing, padding, and margins in dp/px as specified
   - Use the exact font styles (family, weight, size, line height)
   - Implement correct border radius values (4px for most elements)
   - Match component heights, widths, and proportions exactly

2. **COMPONENT IMPLEMENTATION**:
   - Create reusable components that match the design system
   - Implement proper state handling (normal, focused, error, disabled)
   - Ensure interactive elements have proper feedback states
   - Implement exact animations and transitions if specified

3. **ASSETS AND RESOURCES**:
   - CRITICAL: Download and implement all SVG assets directly from Figma using the export function
   - If SVG implementation has issues, provide PNG alternatives at 1x, 2x, and 3x resolutions
   - Implement proper asset sizing with exact dimensions from the design
   - For logos, ensure proper spacing and alignment between logo mark and text components
   - Test all assets on different screen densities to ensure proper scaling
   - SVG Complex Components: For components containing multiple combined SVG files, DO NOT load individual SVG files separately. Instead, process the entire SVG component as a complete unit.
   - Export the entire complex SVG component as a single SVG file from Figma before implementation.
   - Use inline SVG or SVG sprites to ensure accurate display as in the design.
   - When encountering complex SVG components, request a preview of the entire component as a unit to ensure design integrity.
   - Perform comparison checks between the rendered result and original design, paying special attention to alignment and relative sizes between SVG elements.

4. **TEXT AND TYPOGRAPHY**:
   - Use exact text content as shown in the design
   - Implement proper text truncation and overflow handling
   - Match text alignment and positioning precisely
   - Ensure font weights match exactly (400, 500, 600, 700)

5. **RESPONSIVE BEHAVIOR**:
   - Implement responsive layouts that maintain design integrity
   - Handle different screen sizes appropriately
   - Ensure touch targets meet minimum size requirements (48dp)
   - Test on both small and large screens to verify layout consistency

6. **ACCESSIBILITY**:
   - Implement proper semantic markup for accessibility
   - Ensure sufficient color contrast for text elements
   - Provide appropriate content descriptions for images

7. **TESTING AND VALIDATION**:
   - Include tests to verify visual accuracy
   - Validate implementation against design specifications
   - Test on multiple devices and screen sizes
   - Provide side-by-side comparison screenshots of implementation vs. design

8. **IMPLEMENTATION VERIFICATION**:
   - After implementing each major component, verify against Figma using overlay techniques
   - For complex components, provide progress updates with comparison screenshots
   - Address any visual discrepancies immediately before proceeding

9. **ASSET HANDLING**:
   - For complex graphical elements like logos, prefer using a single SVG file rather than breaking it into separate components
   - Download and use complete SVG exports directly from Figma when available
   - Only decompose graphics into separate files when animation or interactive behavior requires it

Please reference the Figma design at all times during implementation and verify each component against the design before completion. Do not include any device frame elements in the implementation. **Ensure that the implementation is production-ready and follows best practices for the target framework. Do not hallucinate or make assumptions about the design; always refer to the Figma design for accurate implementation. If can't connect figma design, please retry ultil you can connect.**

Figma design URL: `{{DESIGN_URL}}`
Target framework: `{{FRAMEWORK}}`
Additional requirements: `{{REQUIREMENTS}}`