import React from 'react';

const LandingPage = () => {
  return (
    <div className="min-h-screen bg-gray-900 text-gray-300 font-['Playfair Display'] p-8">
      <div className="max-w-4xl mx-auto space-y-12 animate-slide-up">
        <header className="space-y-4">
          <h1 className="text-4xl font-medium">Features</h1>
          <h2 className="text-3xl font-medium text-blue-400">
            Supercharge Your Market Research with Entrakit LLC 🚀
          </h2>
          <p className="text-xl">
            <strong>Unlock insights instantly for any product or business.</strong> Entrakit LLC transforms weeks of market research into seconds, empowering you to focus on execution and strategy.
          </p>
        </header>

        <section className="space-y-6">
          <h3 className="text-2xl font-medium">How It Works:</h3>
          <ol className="space-y-4 list-decimal list-inside">
            <li>Enter any product or business URL into Entrakit's platform.</li>
            <li>Let our AI engine analyze data and generate detailed reports within moments.</li>
            <li>Explore actionable insights, including buyer personas, SWOT analyses, growth opportunities, and more.</li>
          </ol>
        </section>

        <section className="space-y-6">
          <h3 className="text-2xl font-medium">What You Get:</h3>
          <div className="space-y-4">
            <div className="p-4 bg-gray-800 rounded-lg">
              <h4 className="font-medium text-blue-400">Deep Buyer Persona Research</h4>
              <p>Understand your target audience—their needs, wants, and motivations—to refine your approach.</p>
            </div>
            <div className="p-4 bg-gray-800 rounded-lg">
              <h4 className="font-medium text-blue-400">Comprehensive SWOT Analysis</h4>
              <p>Evaluate strengths, weaknesses, opportunities, and threats to shape smarter strategies.</p>
            </div>
            <div className="p-4 bg-gray-800 rounded-lg">
              <h4 className="font-medium text-blue-400">Competitive Insights</h4>
              <p>Stay ahead of the market with real-time intelligence on competitors and trends.</p>
            </div>
            <div className="p-4 bg-gray-800 rounded-lg">
              <h4 className="font-medium text-blue-400">Growth Opportunity Identification</h4>
              <p>Discover untapped opportunities and market gaps tailored to your business goals.</p>
            </div>
          </div>
        </section>

        <section className="space-y-6">
          <h3 className="text-2xl font-medium">Why Entrakit LLC?</h3>
          <ul className="list-disc list-inside space-y-2">
            <li>Save time and resources by automating complex research tasks.</li>
            <li>Generate high-quality leads and optimize customer engagement.</li>
            <li>Make data-driven decisions with confidence.</li>
          </ul>
        </section>

        <section className="space-y-6">
          <h3 className="text-2xl">Ready to elevate your market research game?</h3>
          <p>Start now and see how Entrakit LLC can unlock growth for your business.</p>
          <div className="space-y-4">
            <h4 className="text-xl font-medium">Get Started Today!</h4>
            <p>Sign up or try Entrakit LLC now to experience the power of AI-driven market insights.</p>
            <button className="bg-blue-600 text-white px-6 py-2 rounded-lg hover:bg-blue-700 transition-colors">
              Sign Up with Google
            </button>
            <p className="text-sm">
              By creating an account, you agree to our{' '}
              <a href="#" className="text-blue-400 hover:underline">Terms of Service</a> and{' '}
              <a href="#" className="text-blue-400 hover:underline">Privacy Policy</a>.
            </p>
          </div>
        </section>
      </div>
    </div>
  );
};

export default LandingPage;--

---

