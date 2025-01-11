# Naturesque-Typography-System

import React from 'react';

const TypographySystem = () => {
  return (
    <div className="max-w-4xl mx-auto p-8 bg-white">
      <div className="mb-12">
        <h1 className="text-4xl font-bold mb-6 text-gray-800">Naturesque Typography System</h1>
        <p className="text-gray-600 mb-4">A typography system that bridges traditional Ayurvedic wisdom with modern wellness</p>
      </div>

      {/* Primary Heading Font */}
      <div className="mb-12">
        <h2 className="text-2xl font-bold mb-4 text-gray-800">Display/Primary Headlines</h2>
        <div className="bg-gray-50 p-6 rounded-lg mb-4">
          <h3 className="font-serif text-4xl mb-2 text-gray-800">Cormorant Garamond</h3>
          <div className="grid gap-4">
            <div>
              <p className="font-serif text-5xl mb-2">Ancient Wisdom, Modern Wellness</p>
              <p className="text-gray-500 text-sm">Font: Cormorant Garamond Bold - 48px/58px</p>
            </div>
            <div>
              <p className="font-serif text-4xl mb-2">Discover Natural Healing</p>
              <p className="text-gray-500 text-sm">Font: Cormorant Garamond Medium - 40px/48px</p>
            </div>
          </div>
          <div className="mt-4 p-4 bg-gray-100 rounded">
            <p className="text-sm text-gray-600">Use for: Hero headlines, section titles, main product names</p>
          </div>
        </div>
      </div>

      {/* Secondary Heading Font */}
      <div className="mb-12">
        <h2 className="text-2xl font-bold mb-4 text-gray-800">Secondary Headlines</h2>
        <div className="bg-gray-50 p-6 rounded-lg mb-4">
          <h3 className="text-xl mb-2 text-gray-800">Plus Jakarta Sans</h3>
          <div className="grid gap-4">
            <div>
              <p className="text-3xl font-semibold mb-2">Product Benefits</p>
              <p className="text-gray-500 text-sm">Font: Plus Jakarta Sans SemiBold - 30px/38px</p>
            </div>
            <div>
              <p className="text-2xl font-semibold mb-2">Key Ingredients</p>
              <p className="text-gray-500 text-sm">Font: Plus Jakarta Sans SemiBold - 24px/32px</p>
            </div>
          </div>
          <div className="mt-4 p-4 bg-gray-100 rounded">
            <p className="text-sm text-gray-600">Use for: Product features, category headers, section subtitles</p>
          </div>
        </div>
      </div>

      {/* Body Text */}
      <div className="mb-12">
        <h2 className="text-2xl font-bold mb-4 text-gray-800">Body Text</h2>
        <div className="bg-gray-50 p-6 rounded-lg mb-4">
          <h3 className="text-xl mb-2 text-gray-800">Inter</h3>
          <div className="grid gap-6">
            <div>
              <p className="text-lg mb-2">Primary Body Text</p>
              <p className="leading-relaxed mb-2">Experience the transformative power of ancient Ayurvedic ingredients, carefully selected and scientifically validated for modern wellness needs.</p>
              <p className="text-gray-500 text-sm">Font: Inter Regular - 16px/24px</p>
            </div>
            <div>
              <p className="text-base mb-2">Secondary Body Text</p>
              <p className="leading-relaxed text-sm mb-2">Our products combine traditional wisdom with contemporary research to deliver optimal results. Each ingredient is carefully sourced and tested for purity.</p>
              <p className="text-gray-500 text-sm">Font: Inter Regular - 14px/21px</p>
            </div>
          </div>
          <div className="mt-4 p-4 bg-gray-100 rounded">
            <p className="text-sm text-gray-600">Use for: Product descriptions, ingredient details, general content</p>
          </div>
        </div>
      </div>

      {/* UI Elements */}
      <div className="mb-12">
        <h2 className="text-2xl font-bold mb-4 text-gray-800">UI Elements</h2>
        <div className="bg-gray-50 p-6 rounded-lg mb-4">
          <h3 className="text-xl mb-2 text-gray-800">Plus Jakarta Sans</h3>
          <div className="grid gap-4">
            <div>
              <button className="bg-green-600 text-white px-6 py-3 rounded-full font-medium">Shop Now</button>
              <p className="text-gray-500 text-sm mt-2">Font: Plus Jakarta Sans Medium - 14px/20px</p>
            </div>
            <div>
              <p className="uppercase tracking-wider text-sm font-medium">Navigation Menu</p>
              <p className="text-gray-500 text-sm mt-2">Font: Plus Jakarta Sans Medium - 12px/16px</p>
            </div>
          </div>
          <div className="mt-4 p-4 bg-gray-100 rounded">
            <p className="text-sm text-gray-600">Use for: Buttons, navigation, labels, tags</p>
          </div>
        </div>
      </div>

      {/* CSS Implementation */}
      <div className="mb-12">
        <h2 className="text-2xl font-bold mb-4 text-gray-800">CSS Implementation</h2>
        <div className="bg-gray-800 p-6 rounded-lg text-green-400 font-mono text-sm">
          <pre>{`@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600;700&family=Inter:wght@400;500;600&family=Plus+Jakarta+Sans:wght@400;500;600&display=swap');

:root {
  --font-display: 'Cormorant Garamond', serif;
  --font-body: 'Inter', sans-serif;
  --font-ui: 'Plus Jakarta Sans', sans-serif;
}

/* Display Headlines */
h1, .h1 {
  font-family: var(--font-display);
  font-weight: 700;
  font-size: 48px;
  line-height: 58px;
}

/* Secondary Headlines */
h2, .h2 {
  font-family: var(--font-ui);
  font-weight: 600;
  font-size: 30px;
  line-height: 38px;
}

/* Body Text */
body {
  font-family: var(--font-body);
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
}

/* UI Elements */
.button, 
.nav-item {
  font-family: var(--font-ui);
  font-weight: 500;
  font-size: 14px;
  line-height: 20px;
}`}</pre>
        </div>
      </div>
    </div>
  );
};

export default TypographySystem;
