‌# Summary​

* [Upgrade](Upgrade.md)
* [Changelog](CHANGELOG.md)
* [About These Examples](features/about_these_examples.md)
* [License](LICENSE)
* [Contributing](CONTRIBUTING.md)

## Cassettes

* [Cassette Format](features/cassettes/format.md)
* [Naming](features/cassettes/naming.md)
* [Error for HTTP Request Made When No Cassette Is in Use](features/cassettes/no_cassette.md)
* [Dynamic ERB Cassettes](features/cassettes/no_cassette.md)
* [Automatic Re-Recording](features/cassettes/automatic_re_recording.md)
* [Exclusive Cassette](features/cassettes/exclusive.md)
* [Update Content Length Header](features/cassettes/update_content_length_header.md)
* [Decode Compressed Response](features/cassettes/decompress.md)
* [Allow Unused HTTP Interactions](features/cassettes/allow_unused_http_interactions.md)
* [Freezing Time](features/cassettes/freezing_time.md)

## Record modes

* [Once](features/record_modes/once.md)
* [New Episodes](features/record_modes/new_episodes.md)
* [None](features/record_modes/none.md)
* [All](features/record_modes/all.md)
* [Record on Error](features/record_modes/record_on_error.md)

## Configuration

* [Cassette Library Dir](features/configuration/cassette_library_dir.md)
* [Hook Into](features/configuration/hook_into.md)
* [Default Cassette Options](features/configuration/default_cassette_options.md)
* [Ignore Request](features/configuration/ignore_request.md)
* [Filter Sensitive Data](features/configuration/filter_sensitive_data.md)
* [Allow HTTP Connections When No Cassette](features/configuration/allow_http_connections_when_no_cassette.md)
* [Debug Logging](features/configuration/debug_logging.md)
* [Preserve Exact Body Bytes](features/configuration/preserve_exact_body_bytes.md)
* [URI Parser](features/configuration/uri_parser.md)
* [Query Parser](features/configuration/query_parser.md)

## Hooks

* [Before Record Hook](features/hooks/before_record.md)
* [Before Playback Hook](features/hooks/before_playback.md)
* [Before HTTP Request Hook](features/hooks/before_http_request.md)
* [After HTTP Request Hook](features/hooks/after_http_request.md)
* [Around HTTP Request Hook](features/hooks/around_http_request.md)

## Request matching

* [Introduction](features/request_matching/README.md)
* [Matching on Method](features/request_matching/method.md)
* [Matching on URI](features/request_matching/uri.md)
* [Matching on Host](features/request_matching/host.md)
* [Matching on Path](features/request_matching/path.md)
* [Matching on Query String](features/request_matching/query.md)
* [Matching on Body](features/request_matching/body.md)
* [Matching on Headers](features/request_matching/headers.md)
* [Identical Requests Are Replayed in Sequence](features/request_matching/identical_request_sequence.md)
* [Register and Use a Custom Matcher](features/request_matching/custom_matcher.md)
* [URI Without Param(s)](features/request_matching/uri_without_param.md)
* [Playback Repeats](features/request_matching/playback_repeats.md)
* [Matching on Body as JSON](features/request_matching/body_as_json.md)

## Test frameworks

* [Usage With Test::Unit](features/test_frameworks/test_unit.md)
* [Usage With RSpec Metadata](features/test_frameworks/rspec_metadata.md)
* [Usage With Cucumber](features/test_frameworks/cucumber.md)

## Middleware

* [Rack](features/middleware/rack.md)
* [Faraday Middleware](features/test_frameworks/faraday.md)

## HTTP Libraries

* [Net::HTTP](features/http_libraries/net_http.md)
* [EM HTTP Request](features/http_libraries/em_http_request.md)
