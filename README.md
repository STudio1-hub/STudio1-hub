export default function HomePage() {
  return (
    <div className="min-h-screen flex">
      {/* Left Side */}
      <div className="w-1/2 bg-white p-10 flex flex-col justify-center">
        <h1 className="text-4xl font-bold mb-4">Sara Toldi</h1>
        <p className="text-lg mb-2">24</p>
        <p className="text-lg mb-2">Hungary</p>
        <p className="text-lg">Living in the Netherlands</p>
      </div>

      {/* Right Side */}
      <div className="w-1/2 bg-gray-100 p-10 grid grid-cols-2 gap-4 overflow-y-auto">
        {/* Example photo placeholders */}
        <div className="aspect-square bg-gray-300 rounded-lg" />
        <div className="aspect-square bg-gray-300 rounded-lg" />
        <div className="aspect-square bg-gray-300 rounded-lg" />
        <div className="aspect-square bg-gray-300 rounded-lg" />
        {/* You can add <img src="..." alt="photo" /> tags instead of the gray blocks */}
      </div>
    </div>
  );
}
