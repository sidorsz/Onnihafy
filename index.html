import React, { useState, useEffect } from 'react';
import { 
  Home, Search, Library, Heart, Radio, 
  Play, Pause, SkipBack, SkipForward, 
  Volume2, Shuffle, Repeat, Share2, Bell,
  User, Clock, Settings, LogOut
} from 'lucide-react';

// Mock data for demonstration
const mockSongs = [
  { id: 1, title: "Bohemian Rhapsody", artist: "Queen", album: "A Night at the Opera", duration: "5:55", cover: "/api/placeholder/300/300" },
  { id: 2, title: "Stairway to Heaven", artist: "Led Zeppelin", album: "Led Zeppelin IV", duration: "8:02", cover: "/api/placeholder/300/300" },
  { id: 3, title: "Hotel California", artist: "Eagles", album: "Hotel California", duration: "6:30", cover: "/api/placeholder/300/300" },
];

const mockPlaylists = [
  { id: 1, name: "My Favorites", songCount: 125 },
  { id: 2, name: "Rock Classics", songCount: 50 },
  { id: 3, name: "Workout Mix", songCount: 75 },
];

const mockRadioStations = [
  { id: 1, name: "Rock Radio", genre: "Rock", listeners: "15K" },
  { id: 2, name: "Jazz FM", genre: "Jazz", listeners: "8K" },
  { id: 3, name: "Pop Hits", genre: "Pop", listeners: "25K" },
];

const MusicStreamingApp = () => {
  const [currentView, setCurrentView] = useState('home');
  const [isPlaying, setIsPlaying] = useState(false);
  const [currentSong, setCurrentSong] = useState(null);
  const [volume, setVolume] = useState(80);
  const [searchQuery, setSearchQuery] = useState('');
  const [isUserMenuOpen, setIsUserMenuOpen] = useState(false);
  const [notifications, setNotifications] = useState([]);

  // Main Layout Component
  const Layout = ({ children }) => (
    <div className="h-screen w-full bg-gradient-to-b from-gray-900 to-black text-white flex">
      {/* Sidebar */}
      <div className="w-64 bg-black p-6 flex flex-col">
        <div className="mb-8">
          <h1 className="text-2xl font-bold mb-8">Onnihafy</h1>
          <nav className="space-y-6">
            <button onClick={() => setCurrentView('home')} 
                    className="flex items-center gap-4 hover:text-white/80 transition">
              <Home size={20} />
              <span>Home</span>
            </button>
            <button onClick={() => setCurrentView('search')}
                    className="flex items-center gap-4 hover:text-white/80 transition">
              <Search size={20} />
              <span>Search</span>
            </button>
            <button onClick={() => setCurrentView('library')}
                    className="flex items-center gap-4 hover:text-white/80 transition">
              <Library size={20} />
              <span>Your Library</span>
            </button>
            <button onClick={() => setCurrentView('radio')}
                    className="flex items-center gap-4 hover:text-white/80 transition">
              <Radio size={20} />
              <span>Radio</span>
            </button>
          </nav>
        </div>

        {/* Playlists */}
        <div className="flex-1">
          <h2 className="text-lg font-semibold mb-4">Your Playlists</h2>
          <div className="space-y-4">
            {mockPlaylists.map(playlist => (
              <div key={playlist.id} className="flex items-center justify-between hover:bg-white/10 p-2 rounded">
                <span>{playlist.name}</span>
                <span className="text-sm text-gray-400">{playlist.songCount} songs</span>
              </div>
            ))}
          </div>
        </div>

        {/* User Menu */}
        <div className="relative">
          <button 
            onClick={() => setIsUserMenuOpen(!isUserMenuOpen)}
            className="flex items-center gap-2 hover:bg-white/10 p-2 rounded w-full"
          >
            <User size={20} />
            <span>John Doe</span>
          </button>
          {isUserMenuOpen && (
            <div className="absolute bottom-full left-0 w-full bg-gray-800 rounded-lg p-2 shadow-lg">
              <button className="flex items-center gap-2 hover:bg-white/10 p-2 rounded w-full">
                <Settings size={16} />
                <span>Settings</span>
              </button>
              <button className="flex items-center gap-2 hover:bg-white/10 p-2 rounded w-full text-red-400">
                <LogOut size={16} />
                <span>Logout</span>
              </button>
            </div>
          )}
        </div>
      </div>

      {/* Main Content */}
      <div className="flex-1 overflow-auto">
        {/* Header */}
        <header className="p-6 flex items-center justify-between sticky top-0 bg-gradient-to-b from-gray-900 to-transparent">
          <div className="flex-1 max-w-xl">
            <div className="relative">
              <Search size={20} className="absolute left-3 top-1/2 transform -translate-y-1/2 text-gray-400" />
              <input
                type="text"
                placeholder="Search for songs, artists, or albums..."
                className="w-full bg-white/10 rounded-full py-2 pl-10 pr-4 focus:outline-none focus:ring-2 focus:ring-white/20"
                value={searchQuery}
                onChange={(e) => setSearchQuery(e.target.value)}
              />
            </div>
          </div>
          <div className="flex items-center gap-4">
            <button className="relative">
              <Bell size={20} />
              <span className="absolute -top-1 -right-1 w-4 h-4 bg-red-500 rounded-full text-xs flex items-center justify-center">
                3
              </span>
            </button>
          </div>
        </header>

        {/* Content */}
        <main className="p-6">
          {currentView === 'home' && (
            <div className="space-y-8">
              {/* Featured Section */}
              <section>
                <h2 className="text-2xl font-bold mb-4">Featured</h2>
                <div className="grid grid-cols-3 gap-4">
                  {mockSongs.map(song => (
                    <div 
                      key={song.id}
                      className="bg-white/5 rounded-lg p-4 hover:bg-white/10 transition cursor-pointer"
                      onClick={() => {
                        setCurrentSong(song);
                        setIsPlaying(true);
                      }}
                    >
                      <img src={song.cover} alt={song.title} className="w-full aspect-square object-cover rounded-lg mb-4" />
                      <h3 className="font-semibold">{song.title}</h3>
                      <p className="text-sm text-gray-400">{song.artist}</p>
                    </div>
                  ))}
                </div>
              </section>

              {/* Radio Stations */}
              <section>
                <h2 className="text-2xl font-bold mb-4">Radio Stations</h2>
                <div className="grid grid-cols-3 gap-4">
                  {mockRadioStations.map(station => (
                    <div key={station.id} className="bg-white/5 rounded-lg p-4 hover:bg-white/10 transition cursor-pointer">
                      <h3 className="font-semibold">{station.name}</h3>
                      <p className="text-sm text-gray-400">{station.genre}</p>
                      <p className="text-sm text-gray-400">{station.listeners} listeners</p>
                    </div>
                  ))}
                </div>
              </section>
            </div>
          )}
        </main>
      </div>

      {/* Player Bar */}
      <div className="fixed bottom-0 left-0 right-0 bg-gray-900 border-t border-white/10 p-4">
        <div className="max-w-screen-xl mx-auto flex items-center justify-between">
          {/* Current Song Info */}
          <div className="flex items-center gap-4 w-1/4">
            {currentSong && (
              <>
                <img src={currentSong.cover} alt={currentSong.title} className="w-14 h-14 rounded" />
                <div>
                  <h4 className="font-semibold">{currentSong.title}</h4>
                  <p className="text-sm text-gray-400">{currentSong.artist}</p>
                </div>
              </>
            )}
          </div>

          {/* Player Controls */}
          <div className="flex flex-col items-center w-2/4">
            <div className="flex items-center gap-4 mb-2">
              <button className="text-gray-400 hover:text-white transition">
                <Shuffle size={20} />
              </button>
              <button className="text-gray-400 hover:text-white transition">
                <SkipBack size={20} />
              </button>
              <button 
                className="w-10 h-10 rounded-full bg-white text-black flex items-center justify-center hover:scale-105 transition"
                onClick={() => setIsPlaying(!isPlaying)}
              >
                {isPlaying ? <Pause size={20} /> : <Play size={20} />}
              </button>
              <button className="text-gray-400 hover:text-white transition">
                <SkipForward size={20} />
              </button>
              <button className="text-gray-400 hover:text-white transition">
                <Repeat size={20} />
              </button>
            </div>
            {/* Progress Bar */}
            <div className="w-full flex items-center gap-2">
              <span className="text-xs text-gray-400">2:30</span>
              <div className="flex-1 h-1 bg-white/20 rounded-full">
                <div className="w-1/3 h-full bg-white rounded-full"></div>
              </div>
              <span className="text-xs text-gray-400">4:15</span>
            </div>
          </div>

          {/* Volume Control */}
          <div className="flex items-center gap-2 w-1/4 justify-end">
            <Volume2 size={20} />
            <input
              type="range"
              min="0"
              max="100"
              value={volume}
              onChange={(e) => setVolume(e.target.value)}
              className="w-24"
            />
          </div>
        </div>
      </div>
    </div>
  );

  return <Layout>{/* Content will be rendered inside Layout */}</Layout>;
};

export default MusicStreamingApp;
