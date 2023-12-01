# opennurbsStatic

	git clone -b bonsmile https://github.com/bonsmile/opennurbs
	cmake -S . --preset msvc-Release
	cmake --build ./out/build/msvc-Release --config Release --target opennurbsStatic 
	cmake --build ./out/build/msvc-Release --config Release --target install
	cmake -S . --preset msvc-Debug
	cmake --build ./out/build/msvc-Debug --config Debug --target opennurbsStatic 
	cmake --build ./out/build/msvc-Debug --config Debug --target install